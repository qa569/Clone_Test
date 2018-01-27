pipeline {
  agent any
  stages {
    stage('Test stage') {
      steps {
        build(job: 'test job', quietPeriod: 1)
      }
    }
  }
}