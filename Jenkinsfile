pipeline {
    agent any 
    stages {
        stage ('Ejercicio2') {
            steps {
                sh '''
                lineas_fichero=$release.yml
                for i in $lineas_fichero;
                do
                echo $i
                echo "$lineas_fichero"
                done
                '''
                }
            }
        }
    }