pipeline {
	agent { label 'dev' }
    stages {
        stage(checkout) {
            steps {
                sh 'git clone https://github.com/manju001/java-mvn-hello-world-web-app'
            }
        }
	stage(mvnprocess) {
            steps { 
                sh 'mvn install'
            }
        }
    }
}
