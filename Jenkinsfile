pipeline {
    agent {
        label 'linux'
    }
    tools {
        maven 'M3'
    }
    stages {
        stage("checkout") {
            steps {
                git 'https://github.com/garyli94110/hello-jenkins.git'
            }
        }
        stage("build") {
            steps {
                sh "mvn clean compile"
            }
        }

    }
}