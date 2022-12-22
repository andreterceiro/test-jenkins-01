pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage("abc") {
            steps {
                sh "ping 127.0.0.1 -c4"
                sh "firefox"
            }
        }
        stage("cat-teste.txt") {
            steps {
                sh "cat teste.txt"
            }
        }
    }
}
