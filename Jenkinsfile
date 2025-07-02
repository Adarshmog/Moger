pipeline {
    agent { label 'linux-agent' }

    stages {
        stage('Step 1: Hello') {
            steps {
                echo '👋 Hello from Linux Agent!'
            }
        }

        stage('Step 2: Directory') {
            steps {
                sh 'pwd'
                sh 'ls -l'
            }
        }

        stage('Step 3: Done') {
            steps {
                echo '✅ Pipeline Finished Successfully!'
            }
        }
    }
}
