pipeline {
    agent any

    stages {
        stage('Startup') {
            steps {
                echo 'Build is going to start... '
            }
        }
        stage('Build') {
            steps {
                echo 'Building...'
                sh 'cd CMake-demo'
                sh './test.sh'
            }
        }
    }
}
