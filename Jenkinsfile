ipeline {
  agent any
  stages {
       stage('Build') {
          steps {
            echo 'Building my app'
          }
        }

        stage('Building') {
          steps {
            echo 'byPass the building'
          }
        }

      }
    }

    stage('Test') {
      steps {
        sh 'df -h'
      }
    }

    stage('Post') {
      steps {
        timestamps()
      }
    }

  }
  environment {
    stages = 'building'
  }
}
