pipeline {
    agent any

    stages {
        stage('Run Python Script') {
            steps {
                script {
                    // Execute the existing Python script
                    sh 'python3 hi.py' // Use 'python' if 'python3' is not available
                }
            }
        }
    }
}
