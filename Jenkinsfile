pipeline {
    agent any
        
        tools {
               jdk "java"
               maven "Maven"
             }


    stages {

       stage('Build') {
         steps {

              sh 'mvn clean package'
              
       }

}

}

}
