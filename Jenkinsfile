pipeline {
    agent any 
    stages {
        stage ('Ejercicio2') {
            steps {
                sh '''
                for i in $(cut -d ':' -f1,2 release.yml);
                do
                echo "$(cut -d ':' -f1,2 release.yml)"
                done
                '''
                }
            }
        }
    }