pipeline {
    agent any

    tools {
        maven 'Maven'
        nodeJS 'nodejs'
    }

    stages {

        stage('Backend - Tests') {
            steps {
                dir('Backend/tp_automatisation_tests') {
                    sh 'mvn clean test'
                }
            }
        }


        
    }
}

