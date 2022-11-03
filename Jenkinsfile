pipeline {
    agent any 
    stages {
        stage ('Ejercicio2') {
            steps {
                sh '''
                for i in `release.yml`;
                do
                echo "$i"
                done
                '''
                }
            }
        }
    }