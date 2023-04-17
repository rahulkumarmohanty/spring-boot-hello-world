pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage("Test"){
            steps{
                sh "mvn clean"
                echo "========executing A========"
            }
        }
        stage("Test1"){
            steps{
                sh "mvn test"
                echo "========executing build========"
            }
        }
        stage("Test2"){
            steps{
                sh "mvn package"
                echo "========executing A========"
            }
        }
        stage("Test3"){
            steps{
                echo "========executing A========"
            }
        }
    }
    post{
        always{
            echo "========always========"
        }
        success{
            echo "========pipeline executed successfully ========"
        }
        failure{
            echo "========pipeline execution failed========"
        }
    }
}