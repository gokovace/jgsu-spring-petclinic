pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}