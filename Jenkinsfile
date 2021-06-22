pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        sh 'echo "It\\\'s a build $BUILD_NUMBER and demo $DEMO"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}