pipeline {

	stages {

        stage('Test') {
	agent any
            steps {
                sh 'docker run -d -p 9999:8080 joetse/hoi:tomcat7.0.84_jdk8u161'
            }
        }
	}
}
