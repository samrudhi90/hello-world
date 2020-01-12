pipeline {
    agent any
        
        tools {
               jdk "Java-1.8"
               maven "Maven-3.6.3"
             }


    stages {

       stage('test') {
         steps {

              sh 'java -version'
              sh 'mvn -version'
       }

}

}

}
