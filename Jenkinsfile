pipeline {
    agent any

    triggers {
        pollSCM('* * * * *')
    }

    stages {

        stage('Checkout') {
            steps {
                checkout scm
            }
        }

        stage('Print Message') {
            steps {
                echo 'CI Pipeline Triggered Successfully!'
            }
        }

        stage('Run Dummy Test') {
            steps {
                sh 'bash test.sh'
            }
        }
    }
}
