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
//         echo "test1"
        sh "bundle exec fastlane build"
      }
    }
  }
}