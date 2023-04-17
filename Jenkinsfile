pipeline{
    agent any
    tools{
        maven 'maven'
    }
    stages{
        stage("Test"){
            steps{
                sh "mvn --version"
                echo "========executing A========"
            }
        }
        stage("Test"){
            steps{
                echo "========executing A========"
            }
        }
        stage("Test"){
            steps{
                echo "========executing A========"
            }
        }
        stage("Test"){
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