pipeline {
    agent any 
    stages {
        stage ('Ejercicio2') {
            steps {
                sh '''
                lineas_fichero=$(cat release.yml)
                for i in $lineas_fichero; do
                echo "El nombre es y la versión $i"
                done
                '''
                }
            }
        }
    }