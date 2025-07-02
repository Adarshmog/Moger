pipeline {
    agent { label 'windows_slave' }

    stages {
        stage('Checkout') {
            steps {
                git url: 'https://github.com/Adarshmog/Moger.git'
            }
        }

        stage('Step 1: Hello') {
            steps {
                echo '👋 Hello from Windows Agent!'
            }
        }

        stage('Step 2: Directory') {
            steps {
                bat 'cd'
                bat 'dir'
            }
        }

        stage('Step 3: Done') {
            steps {
                echo '✅ Pipeline Finished Successfully!'
            }
        }
    }
}
