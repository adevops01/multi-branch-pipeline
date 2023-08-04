pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo "Building branch: ${env.GIT_BRANCH}"  
            }
        }
        stage('Test') {
           steps {
                echo "Testing branch: ${env.GIT_BRANCH}"
           }
        }
        stage('Deploy') {
           steps {
                echo "Deploying ${env.GIT_BRANCH}...."
           }
        }
    }
}
