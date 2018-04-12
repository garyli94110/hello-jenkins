pipeline {
    agent any 
    stages {
        stage("checkout") {
            steps {
                git 'https://github.com/garyli94110/hello-jenkins.git'
            }
        }
        stage("build") {
            steps {
                echo "mvn clean compile"
            }
        }

    }
}
