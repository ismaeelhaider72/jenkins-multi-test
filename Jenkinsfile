pipeline {
    agent any

    triggers {
        // This line prevents the job from running automatically
        cron('H H(0-23) * * *')
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building... dev'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing... dev'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying... dev'
            }
        }
    }
}
