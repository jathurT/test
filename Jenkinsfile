pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                script {
                    // Use 'bat' for Windows
                    bat 'python hi.py'
                }
            }
        }
    }
}
