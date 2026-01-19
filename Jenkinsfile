pipeline {
    agent any

    stages {

        stage('Unit') {
            steps {
                echo 'Ejecutando pruebas unitarias'
            }
        }

        stage('Rest') {
            steps {
                echo 'Ejecutando pruebas REST'
            }
        }

        stage('Static') {
            steps {
                echo 'Análisis estático con flake8'
            }
        }

        stage('Security Test') {
            steps {
                echo 'Análisis de seguridad con bandit'
            }
        }

        stage('Coverage') {
            steps {
                echo 'Cobertura de código'
            }
        }

        stage('Performance') {
            steps {
                echo 'Pruebas de rendimiento con JMeter'
            }
        }
    }
}
