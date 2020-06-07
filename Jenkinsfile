#!/usr/bin/env groovy

pipeline {
  agent any
  stages {
    stage('mvn clean install') {
      steps {
        bat 'mvn clean install'
      }
    }
  }
}