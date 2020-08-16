pipeline{
    agent any
    stages{
        stage("build"){
            steps{
                echo "building"
                javac Hello.java
                java Hello
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
