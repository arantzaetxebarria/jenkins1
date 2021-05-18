pipeline {
    agent any

    stages {
        stage('Fecha') {
            steps {
                sh 'date'
            }
        }
        stage('Usuarios') {
            steps {
                sh 'wc -l /etc/passwd'
            }
        }
    }
}
