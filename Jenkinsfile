pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                git branch: 'agmcicdnodejs', url: 'https://github.com/AananthGopalan965/skillupnodejs.git'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying artifacts...'
            }
        }
    }
}
