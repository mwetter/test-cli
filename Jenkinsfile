#!groovy

node{
  stage('Build'){
    sh 'sudo pip install --upgrade git+https://github.com/lbl-srg/BuildingsPy@cli-testing'
  }
  stage('Test'){
    checkout scm    
    sh 'git clean -f && cd Buildings && python ../bin/runUnitTests.py -b'
  }
}
