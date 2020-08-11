pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
				bat 'dir'
				bat 'node index.js'
            }
        }
    }
}