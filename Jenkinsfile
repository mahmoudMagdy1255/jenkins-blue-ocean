pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'Build Completed'
        retry(count: 2) {
          sh 'wwwwwwwwwwwwwwwwww'
        }

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
        input(message: 'Are you sure for deploy ? ', ok: 'Yes, Iam sure', cancel: 'No')
      }
    }

  }
}