pipeline {
    agent any

    stages {
        stage('clean') {
            steps {
                echo 'cleaning..'
		sh '/home/ubuntu/maven/apache-maven-3.6.3/bin/mvn clean'
            }
        }
        stage('Package') {
            steps {
                echo 'Testing..'
		sh 'mvn package'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'                
            }
        }
    }
}
