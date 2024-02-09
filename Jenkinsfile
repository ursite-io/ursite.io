pipeline {
  agent any
  stages {
    stage('publish') {
      steps {
        git(url: 'https://github.com/ursite-io/ursite.io', branch: 'main')
      }
    }

  }
}