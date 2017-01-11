#!groovy

node{
  checkout scm
  stage('Build'){
    sh 'sudo pip install git+https://github.com/lbl-srg/BuildingsPy'
  }
  stage('Test'){
    sh 'python bin/runUnitTests.py'
  }
}
