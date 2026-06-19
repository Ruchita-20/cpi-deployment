@Library('piper-lib') _

node() {
    
    stage('Check') {
        bat 'where sh'
        bat 'echo %PATH%'
    }
    
    stage('Init') {
        deleteDir()
        checkout scm
    }

    stage('Deploy') {
        integrationArtifactDeploy script: this
    }
}
