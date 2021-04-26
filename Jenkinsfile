pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                    echo $SHELL
                '''
            }
        }
        stage('2nd stage') {
            steps {
                sh 'echo "second Stage"'
            }
        }
    }
}
