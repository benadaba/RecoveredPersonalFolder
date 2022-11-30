pipeline{
    agent any

    environment {
        WORKINGDIR = "/usr/herbert"
    }

   tools {
        git 'Default'
        jdk 'jdk8'
    }

    stages {
        stage("Stage1"){
            steps{
                sh "pwd"
                 echo "I love jenkins"
            }
        }
    stage("Stage2"){
            steps{
                echo "Stage 2 step2"
                echo "I love jenkins 222 222"
            }
        }
    
   }

}