pipeline{
  agents any
    stages{
      stage('Build'){
        steps{
        echo 'Running Automation Build'
        sh './gradlew build --no-daemon'
        archiveArtificats artifacts: 'dist/trainSchedule.zip'
      }  
    }
  }
}
