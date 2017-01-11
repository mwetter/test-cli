node{
  checkout scm
  stage('Build'){
    sh 'sudo pip install git+https://github.com/lbl-srg/BuildingsPy'
#    sh 'sudo docker images'
  }
  stage('Test'){
    sh 'python bin/runUnitTests.py'
  }
}
