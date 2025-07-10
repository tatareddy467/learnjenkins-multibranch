pipeline {
    agent any 
    environment {
        login = credentials('naani-user-jenkins-slave')
        name = "Naani"
    }
    stages {
        stage ("Build") {
            steps {
                echo "Git hub credentials are ${login}"
                echo "User id is ${login_USR}"
                echo "User password is ${login_PSW}"
            }
        }
    }
}
