pipeline {
    agent any 
    stages {
        stage ('Build') {
            steps {
                echo "Executing Multi branch pipeline from github"
            }
        }
        stage ('test') {
            steps {
                echo "Executing test stage"
            }
        }
        stage ('deploytodev') {
            steps {
                echo "Executing to dev deployment stage"
            }
        }
        stage ('deploytoprod') {
            steps {
                echo "Executing to prod deployment stage"
            }
        }
    }
}
