pipeline {
    agent {
        label 'All-Slave'
    }

    stages {
        stage('Dev') {
            steps {
                echo 'This is Dev environment'
            }
        }
        
        stage('Test') {
            steps {
                echo 'This is Test environment'
            }
        }
        
        stage('Prod') {
            steps {
                echo 'This is Production environment'
            }
        }
    }
}
