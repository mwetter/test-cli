#!groovy

node{
  checkout scm
  stage('Build'){
    sh 'sudo pip install git+https://github.com/lbl-srg/BuildingsPy'
  }
  stage('Test'){
    sh '(cd Buildings && python ../bin/runUnitTests.py)'
  }
}
