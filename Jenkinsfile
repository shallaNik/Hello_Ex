pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo "building"
                sh 'hello.py'
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
