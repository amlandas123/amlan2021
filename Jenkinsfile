pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        echo 'Hello World'
        timeout(time: 1, unit: 'MINUTES') {
          sleep 5
          retry(count: 100)
        }

      }
    }

  }
}