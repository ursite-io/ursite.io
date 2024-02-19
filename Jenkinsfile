pipeline {
  agent any
  stages {
    stage('publish') {
      steps {
        git(branch: 'main', url: 'https://github.com/ursite-io/ursite.io')
      }
    }
  }
}
