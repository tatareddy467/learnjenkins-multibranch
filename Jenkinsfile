pipeline {
    agent any
    environment {
        name = "Naani"
        course = "K8S"
    }
    stages {
        stage ('Build') {
            environment {
                cloud = "GCP"
            }
            steps {
                echo "Welcome ${name}"
                echo "You are enrolled to ${course} Course"
                echo "you are certified in ${cloud}"
            }
        }
        stage ('Second Stage') {
            steps {
                echo "Welcome ${name}"
                echo "You are enrolled to ${course} Course"
                echo "you are certified in ${cloud}"                
            }
        }
    }
}
