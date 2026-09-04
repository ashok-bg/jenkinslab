pipeline {
  agent any
 
    stages {
      stage ('build'){
        steps {
          echo 'building'
        }
      }
      stage ('test'){
        when {
          changeset '**/.*sh'
        }
        steps {
          echo 'testing'
        }
      }
        stage ('deploy'){
          steps{
            echo 'deploying'
           }
        }
      }
    }
