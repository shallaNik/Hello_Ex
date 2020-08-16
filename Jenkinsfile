pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo "building"
                javac 
            }
        }
        stage("tetst"){
            steps{
                echo "testing"
            }
        }
        stage("deploy"){
            steps{
                echo "deploying"
            }
        }
    }
}
