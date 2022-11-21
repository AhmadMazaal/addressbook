pipeline {
    agent any
    stages {
        stage('clone the repo') {
            steps {
                git "https://github.com/vaadin/addressbook"
            }
        }
        stage('compile') {
            steps {
                sh "mvn compile"
            }
        }
    }
}
