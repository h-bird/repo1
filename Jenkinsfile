// Jenkinsfile (Declarative Pipeline)
pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    ls -lah
                    ls -al /home
                    id
                    cat /etc/os-release
                '''
            }
        }
    }
}
