@Library('piper-lib') _

node('linux') {
    stage('Init') {
        deleteDir()
        checkout scm
    }

    stage('Deploy') {
        integrationArtifactDeploy script: this
    }
}
