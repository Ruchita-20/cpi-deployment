@Library('piper-lib') _

node() {
  stage('init') {
    deleteDir()
    checkout scm
  }
  stage('integrationArtifactDeploy Command') {
       integrationArtifactDeploy script: this
  }
}
