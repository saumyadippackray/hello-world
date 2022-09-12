pipeline {
    agent any
    tools {
        maven "MAVEN_HOME"
        jdk "JAVA_HOME"
    }
    stages {
        stage('Build') {
            steps {
               echo "PATH = ${M2_HOME}/bin:${PATH}"
                echo "MAVEN_HOME = /opt/maven"
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
