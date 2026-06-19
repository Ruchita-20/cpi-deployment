@Library('piper-lib-os') _

node() {
    
    stage('Init') {
        deleteDir()
        checkout scm
    }

    stage('Deploy') {
        integrationArtifactDeploy script: this
    }
}
