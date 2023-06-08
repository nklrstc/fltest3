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
        sh "bundle exec fastlane build"
      }
    }
  }
}