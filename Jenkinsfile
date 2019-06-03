pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World HIHIHI"'

                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
