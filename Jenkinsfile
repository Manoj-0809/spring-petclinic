pipeline {
    agent any

    stages {

        stage('git clone') {
            steps {
                git url: 'https://github.com/Manoj-0809/spring-petclinic.git'
            }
        }

        stage('maven package') {
            steps {
                sh 'mvn package'
            }
        }

    }
}
