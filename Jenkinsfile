pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''sh \'echo "Hello World"\'
                sh \'\'\'
                    echo "Multiline shell steps work too"
                    ls -lah
                \'\'\''''
        echo 'echo "Hello World"'
      }
    }

  }
}