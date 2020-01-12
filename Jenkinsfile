pipeline {
    agent any
       environment {
          mvnhome= tool "Maven" 
           }
        tools {
               jdk "java"
              // maven "Maven"
             }


    stages {

       stage('Build') {
         steps {
              sh 'echo ${mvnhome}'
              sh 'java -version'
              //sh 'mvn clean package'
              
       }

}

}

}
