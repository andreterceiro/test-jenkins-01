pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                sh "ping 127.0.0.1 -c4"
                sh "firefox"
            }
        }
    }
}
