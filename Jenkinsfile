pipeline{
  agent any
  triggers {
    cron ('H/1 * * * *')
  }
  stages {
    stage('Test'){
      steps{
        echo 'Testing'
      }
    }
  }
}
