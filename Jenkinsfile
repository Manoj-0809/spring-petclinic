pipeline {
    agent any

    stages {

        stage('git clone') {
            steps {
                git url: 'https://github.com/Manoj-0809/spring-petclinic.git'
                    branch: "main"
            }
        }

        stage('maven version') {
            steps {
                sh '''mvn --version'''
            }
        }

    }
}
