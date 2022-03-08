pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo 'This a build number $BUILD_NUMBER'
        sh 'echo "This is build $BUILD_NUMBER of demo $DEMO"'
      }
    }

  }
  environment {
    Demo = '1'
  }
}