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
}
