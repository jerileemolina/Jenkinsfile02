pipeline {
    agent any 
    stages {
        stage ('Ejercicio2') {
            steps {
                sh '''
            IFS=$'\n' 
            for i in $(cat release.yml)
            do 
            echo "La versión de $(echo "$i" | cut -d ":" -f1) es $(echo "$i" | cut -d ":" -f2)"
            done
                '''
                }
            }
        }
    }