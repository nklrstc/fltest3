pipeline {
  agent any
  stages {
    stage('hello') {
      steps {
        echo "Hello world"
      }
    }
    stage('Build') {
      steps {
        echo "Building"
        bat "bundle exec fastlane build"
      }
    }
  }
}