pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo "building"
                python hello.py
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
