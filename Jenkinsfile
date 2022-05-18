pipeline{
    agent any
    stages{
        stage("Clone github"){
            steps{
                 git 'https://github.com/TienMinh1998/jenkinpipeline.git'
            }
        }
         stage("build iamges"){
            steps{
                 echo 'Nguyen Viet Minh Tien'
            }
        }
         stage("devploy"){
            steps{
                 bat 'docker ps'
                 bat 'docker images'
            }
        }
    }
}