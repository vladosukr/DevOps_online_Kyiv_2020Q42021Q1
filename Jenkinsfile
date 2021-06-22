pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo "It\'s a build $BUILD_NUMBER and demo $DEMO"
      }
    }

  }
  environment {
    DEMO = "1"
  }
}
