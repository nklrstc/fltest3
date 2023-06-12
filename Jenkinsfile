#! groovy

pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "Building"
        sh "bundle exec fastlane build"
      }
    }
  }
}