pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                startSastScan path: env.WORKSPACE
            }
        }
    }
    post {
        always {
            // deleteDir()
            echo 'Bypass cleanup.'
        }
    }
}
