pipeline {
    agent {
        docker {
            image 'maven:3.6.3'
        }
        
    }
    stages {
        stage('DockerPythonVersion')
        {
        steps {
            sh 'mvn --version'
            }
        }
    }
}