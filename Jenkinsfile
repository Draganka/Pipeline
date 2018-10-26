pipeline {
  agent any
  stages {
    stage('Test!') {
      steps {
        echo 'print something'
      }
    }
    stage('RepositoryCode') {
      steps {
        git(url: 'https://github.com/Draganka/Pipeline.git', branch: 'master')
      }
    }
  }
}