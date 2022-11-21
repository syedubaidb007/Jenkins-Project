pipeline {
    agent any
    stages {
        stage ("copy files from GitHub"){
            steps {
                sh 'scp -r ${WORKSPACE}/* dev01@192.168.14.143:/var/www/html/Jenkins-Project'
            }
        }
    }
}

