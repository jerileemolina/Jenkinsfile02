pipeline {
    agent any 
    stages {
        stage ('Ejercicio2') {
            steps {
                sh '''
                lineas_fichero=$(`cut -d ':' -f1,2 release.yml`)
                for i in $lineas_fichero;
                do
                echo "$i"
                echo "$lineas_fichero"
                done
                '''
                }
            }
        }
    }