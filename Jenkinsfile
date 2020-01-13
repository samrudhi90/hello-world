pipeline {
    agent any
    parameters {
       choice(name: 'door_choice',
         choices: 'one\ntwo\nthree',
         description: 'What door do u choose?')
       booleanParam(name: 'Can_Dance',
         defaultValue: true,
         description: 'checkbox parameter')
       string(name: 'StrangePARAM',
          defaultValue: 'Dance',
          description: 'Do the funky chicken')
       }
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
              echo "Trying: ${params.door_choice}"
              echo "We can dance: ${params.CAN_DANCE}"
              echo "The DJ says: ${params.StrangePARAM}"
              
       }

}

}

}
