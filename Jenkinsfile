pipeline {
    agent any
    //Defino una variable, se puede poner a nivel general o de stage
    environment {
      FICHERO = "/etc/passwd"
    }

    stages {
        stage('Fecha') {
            steps {
                sh 'date'
            }
        }
        stage('Usuarios') {
            steps {
                sh 'wc -l /$(FICHERO)'
            }
        }
    }
}
