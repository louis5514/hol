pipeline {
    agent any
    tools {
        maven 'M2_HOME'
    }
    
    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
       stage('build') {
            steps {
                echo 'Hello build'
                sh 'mvn clean'
                sh 'mvn install'
                sh 'mvn package'
            }               
       }
        stage('deploy') {
            steps {
                echo 'Hello deploy'
            }
        }
        stage('test') {
            steps {
                echo 'Hello test'
            }
        }
    }
}
