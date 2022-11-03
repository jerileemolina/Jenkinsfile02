pipeline {
    agent any 
    stages {
        stage ('Ejercicio2') {
            steps {
                sh '''
            IFS=$'\n' 
            for i in $(cat ./release.yml)
            do 
            echo "$i" 
            done
                '''
                }
            }
        }
    }