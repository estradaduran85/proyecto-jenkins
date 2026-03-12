pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Descargando el código del repositorio...'
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo 'Construyendo el proyecto...'
            }
        }

        stage('Test') {
            steps {
                echo 'Ejecutando pruebas del proyecto...'
            }
        }

        stage('Deploy Simulation') {
            steps {
                echo 'Simulando despliegue de la aplicación...'
            }
        }

    }
}
