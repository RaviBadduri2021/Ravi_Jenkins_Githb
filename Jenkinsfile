pipeline {
    agent {
        label 'All-Slave'
    }

    stages {
        stage('Hello') {
            steps {
                echo 'This is Dev environment'
            }
        }
        
        stage('Hello') {
            steps {
                echo 'This is Test environment'
            }
        }
        
        stage('Hello') {
            steps {
                echo 'This is Production environment'
            }
        }
    }
}
