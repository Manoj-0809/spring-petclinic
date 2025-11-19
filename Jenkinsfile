pipeline {
    agent any
    stages {
        
        stage("git clone") {
            steps {
                git url: 'https://github.com/Manoj-0809/spring-petclinic.git',
                    branch: "main"
            }
        }

        stage("mvn package") {
            steps {
                sh 'mvn package'
            }
        }
    }
}
