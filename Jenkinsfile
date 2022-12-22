pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
                ping 127.0.0.1 -c4
                firefox
            }
        }
    }
}
