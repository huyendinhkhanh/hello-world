pipeline {
    agent any
    stages {
        stage('Test') {
            steps {
                sh './hello-world.sh'
            }
        }
    }
    post {
        always {
            junit 'build/reports/**/*.xml'
        }
    }
}
