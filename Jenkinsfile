pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed'
      }
    }

    stage('Test 1') {
      parallel {
        stage('Test 1') {
          steps {
            echo 'Test 1'
          }
        }

        stage('Test 2') {
          steps {
            echo 'Test 1'
          }
        }

      }
    }

    stage('Deploy') {
      steps {
        echo 'Deploy Completed'
      }
    }

  }
}