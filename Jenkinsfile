#!/usr/bin/env groovy

pipeline {
  agent any
  stages {
    stage('mvn clean install') {
      steps {
        sh 'mvn clean install'
      }
    }
  }
}