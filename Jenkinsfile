pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage("abc") {
            sh "ping 127.0.0.1 -c4"
            sh "firefox"
        }
        stage("cat-teste.txt") {
            sh "cat teste.txt"
        }
    }
}
