pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/MalikSayyed/react-app.git'
                sh 'npm install'
                sh 'npm run build'
            }
        }
    }
}
