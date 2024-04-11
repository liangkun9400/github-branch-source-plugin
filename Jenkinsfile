/*
 See the documentation for more options:
 https://github.com/jenkins-infra/pipeline-library/
*/
pipline {
  agent { docker { image 'python:3.12.1-alpine3.19' } }
  stage {
    stage('build') {
      steps {
        sh 'python --version'
      }
    }
  }
}
