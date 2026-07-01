@Library('piper-lib@v1.430.0') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  stage('deployIntegrationArtifact Command') {
       integrationArtifactDeploy script: this
  }
}
