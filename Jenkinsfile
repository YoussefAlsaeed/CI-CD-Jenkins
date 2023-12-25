pipeline {
    agent any

    stages {
        stage('Run script') {
            steps {
                sh 'chmod +x ./task.sh'
                sh './task.sh'
            }
        }
    }
}
