pipeline {
    agent any
    stages {
        stage('maven version') {
               steps {
                echo 'checking the maven version'
                bat 'mvn -v'
            }
        }
    
	stage('git cloning') {
               steps {
                echo 'running the clean test'
                git branch: 'main', url: 'https://github.com/nagaraj2018/products_repository.git'
            }
        }
		stage('mvn clean test') {
               steps {
                echo 'running the clean test'
                bat 'mvn clean test'
            }
        }
		stage('Deploy') {
               steps {
                echo 'Deploying the script'
            }
        }
		stage('Release') {
               steps {
                echo 'Releasing the script'
            }
        }
    }
}