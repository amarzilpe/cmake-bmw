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
                sh 'cd $HOME/workspace/cmake'
                sh './test.sh'
            }
        }
    }
}
