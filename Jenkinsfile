pipeline {
    agent any

    stages {

        stage('Print Message') {
            steps {
                echo 'CI Pipeline Triggered Successfully!'
            }
        }

        stage('Run Dummy Test') {
            steps {
                sh 'echo Running dummy test...'
            }
        }
    }
}
