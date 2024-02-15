pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This is build $BUILD_NUMBER of demo $DEMO'
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
        sh 'echo "Hello from Jim!"'
      }
    }

  }
  environment {
    DEMO = '1'
  }
}
