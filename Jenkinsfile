node{
  checkout scm
  stage('Build'){
    sh 'docker -v'
  }
  stage('Test'){
    sh 'python bin/runUnitTests.py'
  }
}
