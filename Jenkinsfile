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
        sh "bundle exec fastlane build"
      }
    }
  }
}