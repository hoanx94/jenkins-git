pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hoa than Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
