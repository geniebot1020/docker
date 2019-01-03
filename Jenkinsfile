pipeline {
    agent {
        docker { image 'joetse/hoi:tomcat7.0.84_jdk8u161' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'touch /tmp/joe'
            }
        }
    }
}
