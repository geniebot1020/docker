pipeline {
    agent none

	stages {

        stage('Test') {
	agent any
            steps {
                sh 'docker run -d joetse/hoi:tomcat7.0.84_jdk8u161'
            }
        }
}
}
