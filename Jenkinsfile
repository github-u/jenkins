pipeline {
    agent {
	docker {image 'maven:3.8.4-jdk-8'}
    } 
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
