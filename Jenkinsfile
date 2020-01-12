pipeline {
    agent any
        
        tools {
               jdk "java"
               maven "maven"
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
