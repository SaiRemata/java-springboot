pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build'
                sh 'mvn clean package'
            }

        }
        stage('Test') {
            steps {
                echo 'Testing'
                sh 'mvn test'
            }
        }
        stage('Quality Gate - Sonar Gate') {
            steps {
                echo 'Sonar Analysis'
            }
        }
        stage('Deploy to dev') {
            steps {
                echo 'Deploy'
            }
        } 
         stage('Dev') {
            steps {
                echo 'Dev Stage'
            }
        }
        stage('Q/A') {
            steps {
                echo 'Q/A'
            }
        }
        stage('UAT') {
            steps {
                echo 'UAT'
            }
        }
        stage('Pre-Prod') {
            steps {
                echo 'Pre-Prod'
            }
        }
        stage('Prod') {
            steps {
                echo 'Prod'
            }
        }

    }
}