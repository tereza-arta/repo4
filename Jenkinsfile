pipeline {
    agent { label 'agent_1' }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello from Jenkinsfile............'
                sh 'docker --version'
            }
        }
    }
}
