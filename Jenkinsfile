pipeline{
    agent any
        stages{

            stage("git clone") (
                steps(
                    git url: 'https://github.com/Manoj-0809/spring-petclinic.git'
                )
            )
        }


        stages  ("maven package") {
            steps { 
                sh 'maven package'
            }
        }   
}
