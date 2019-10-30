pipeline{
    agent any
    stages{
        stage("pull"){
            steps{
                echo "Hello"
            }
        }
        stage("Build"){
            steps{
                bat 'mvn --version'
                bat 'git --version'
            }
        }
    }
}
