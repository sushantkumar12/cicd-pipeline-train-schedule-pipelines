pipeline {
  agents any
  stages{
    stage('Build'){
      steps {
        echo 'Running build Automation'
        sh './gradle build --no-daemon'
        achieveArtifacts artifacts: 'dist/trainSchedule.zip'
      }
    }
  }
}
