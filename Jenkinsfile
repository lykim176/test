Jenkinsfile (Declarative Pipeline)
pipeline {
    agent { docker { image 'maven:3.3.3' } }
    stages {
        stage('build') {
            steps {
				bat (/"C:\apache-maven-3.5.0\bin\mvn" --version /)
            }
        }
    }
}