pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                echo 'Code checked out by Jenkins'
            }
        }

        stage('Build with Maven') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
