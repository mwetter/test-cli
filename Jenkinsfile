node{
  checkout scm
  stage('Build'){
    sh 'docker images'
  }
  stage('Test'){
    sh 'python bin/runUnitTests.py'
  }
}
