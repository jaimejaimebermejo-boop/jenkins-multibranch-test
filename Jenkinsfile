pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Construyendo desde main branch con webhook'
            }
        }
        stage('Test') {
            steps {
                echo 'Probando desde main branch con webhook'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Desplegando desde main branch'
            }
        }
    }
}
