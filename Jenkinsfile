pipeline{
  agent any
  stages{
    stage ('Build'){
        steps{
        echo 'Running Build Automation By @Gaurav'
        sh './gradlew build --no-daemon'
        archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
    }
  }
}
