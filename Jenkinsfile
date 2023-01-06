pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                echo 'Build'
            }

        }
        stage('Test') {
            steps {
                echo 'Testing'
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
        ## This is the Continous Deployment process from here
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

        post {
            failure {
                echo 'I have failed'
            }
            success {
                echo 'I have passed'
            }
            always {
                echo 'I have done Testing'
            }
        }
    }
}