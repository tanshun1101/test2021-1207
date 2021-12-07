pipeline {
  agent {
    node {
      label 'win10'
    }

  }
  stages {
    stage('git pull') {
      steps {
        git 'git@github.com:tanshun1101/test2021-1207.git'
      }
    }

    stage('build') {
      steps {
        bat 'python 1.py'
      }
    }

  }
}