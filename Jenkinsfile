#!groovy
#Prueba

pipeline {
    agent any

    stages {
        stage('Build') {
	    when {
		branch 'master'
	    }
            steps {
                echo 'Building..'
		checkout scm
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
