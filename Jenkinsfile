pipeline {
    agent {
        kubernetes {
            label 'test-pod'
        }
    }
    stages {
        stage('Hello') {
            steps {
                
                container('jnlp') {
                    sh 'echo Hello from JNLP container!'
                }
            }
        }
    }
}
