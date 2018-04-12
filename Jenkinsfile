pipeline {
    agent {
        label 'linux'
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
