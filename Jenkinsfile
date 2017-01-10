node{
  checkout scm
  stage('Build'){
    sh 'sudo docker images'
  }
  stage('Test'){
    sh 'python bin/runUnitTests.py'
  }
}
