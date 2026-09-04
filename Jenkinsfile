pipeline {
  agent any
  triggers {
  cron '* * * * *'
}
    stages {
      stage ('build'){
        steps {
          echo 'building'
        }
      }
        stage ('deploy'){
          steps{
            echo 'deploying'
            sh './hello.sh'
          }
        }
      }
    }
