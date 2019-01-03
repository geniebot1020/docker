pipeline {
    agent none

	stages {
        stage('Test') {
            steps {
                sh 'docker run -d joetse/hoi:tomcat7.0.84_jdk8u161'
            }
        }
}
}
