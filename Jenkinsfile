pipeline {
  agent any
  stages {
    stage('teststage') {
      steps {
        echo 'print this message where?'
        git(url: 'https://github.com/lmstock/jenkingstest', branch: 'main')
      }
    }

  }
}