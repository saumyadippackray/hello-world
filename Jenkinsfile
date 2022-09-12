pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                steps {
                sh 'mvn clean install package'
            }
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
