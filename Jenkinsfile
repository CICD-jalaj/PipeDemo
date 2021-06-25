pipeline {
  agent any
  stages {
    stage('Build') {
      parallel {
        stage('Build') {
          steps {
            echo 'building....'
            echo 'Building...'
            echo 'building....'
          }
        }

        stage('Parellibuilding ') {
          steps {
            echo 'completed....'
          }
        }

      }
    }

    stage('Test') {
      steps {
        echo 'Testing....'
      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploying'
      }
    }

  }
}
