pipeline {
    agent any
    environment {
        DEPLOY_TO = 'production'
    }
    stages {
        stage ('Deploy') {
            when {
                environment name: 'DEPLOY_TO', value: 'productions'
            }
            steps {
                echo "Deploying"
            }
        }
    }
}
