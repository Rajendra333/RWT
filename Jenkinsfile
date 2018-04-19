pipeline {
  agent none
  stages {
    stage('checkout') {
      steps {
        sh 'git checkout'
      }
    }
    stage('build') {
      steps {
        build(job: 'rwt build', quietPeriod: 4)
        sh 'mvn package'
      }
    }
    stage('test') {
      steps {
        sh '''ksdnksd
kddfa]d
'''
      }
    }
  }
  environment {
    dev = 'test'
  }
}