#! groovy

pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        echo "Setup"
      }
    }
    stage('Build') {
      steps {
        echo "Building"
//         echo "test"
        sh "bundle exec fastlane build"
      }
    }
  }
}