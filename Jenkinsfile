pipeline {
    agent any
       def mvnhome= tool "Maven" 
        tools {
               jdk "java"
              // maven "Maven"
             }


    stages {

       stage('Build') {
         steps {
              sh '${mvnhome}'
              sh 'java -version'
              //sh 'mvn clean package'
              
       }

}

}

}
