pipeline {
  agent any
  stages { 'Build'} {
     
     steps {
       echo 'Runing build autoamtion'
       sh './gradlew build --no --daemon'
       archiveArtifacts artifacts: 'sidt/trainSchedule.zip'
       }
      }
    }
  }
  
