def name= "Samrudhi"

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
          def address= "Bangalore"
         steps {
              sh 'echo ${mvnhome}'
              sh 'java -version'
              echo "Name:${name}"
              echo "address:${address}"
              echo "Trying: ${params.door_choice}"
              echo "We can dance: ${params.Can_Dance}"
              echo "The DJ says: ${params.StrangePARAM}"
              
       }

}

}

}
