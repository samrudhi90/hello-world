pipeline {
    agent any
        
        tools {
               jdk "java"
               maven "Maven"
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
