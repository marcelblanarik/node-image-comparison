pipeline {
    agent any

		tools {nodejs "node"}

    stages {
        stage('NPM Install') {
            steps {
                sh 'npm install'
            }
        }
        stage('Run Dev') {
            steps {
                sh 'npm run dev'
            }
        }
    }
}
