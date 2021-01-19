pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '''\'echo "Hello World"\'
\'\'\'
                    echo "Multiline shell steps works too"
                    ls -lah
                \'\'\''''
      }
    }

  }
}