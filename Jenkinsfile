pipeline {
    agent any

    stages {
        stage('Install Apache') {
            steps {
                script {
                    // Update package lists
                    sh 'sudo apt update -y'
                    // Install Apache2
                    sh 'sudo apt install apache2 -y'
    
                }
            }
        }
    }
}
