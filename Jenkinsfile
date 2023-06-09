#!/bin/bash -l

pipeline {
  agent any
  stages {
    stage('Setup') {
      steps {
        echo "Setup"
        sh "gem install bundler"
      }
    }
  }
}