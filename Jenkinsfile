pipeline {
  agent any

  stages {
    stage('Build') {
      steps {
        echo "start ..."
        sh "date"
      }
    }
    stage('Test') {
      steps {
        echo "start ..."
        sh "date"
        sh "sleep 1m"
        sh "exit 1"
      }
    }
    stage('Test 2') {
      steps {
        echo "start ..."
        sh "date"
      }
    }
  }

  post { 
    always { 
      echo 'I will always say Hello again!'
    }
  }
}
