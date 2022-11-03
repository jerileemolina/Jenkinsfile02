pipeline {
    agent any 
    stages {
        stage ('Ejercicio2') {
            steps {
                sh '''
                    for file in *'release.yml'; do
                    echo $file; 
                    done
                '''
                }
            }
        }
    }