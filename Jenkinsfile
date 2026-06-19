@Library('piper-lib') _

node() {
    
    stage('Init') {
        deleteDir()
        checkout scm
    }

    stage('Deploy') {
        integrationArtifactDeploy script: this
    }
}
