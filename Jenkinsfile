pipeline {
    agent any
    tools { 
        maven 'maven-3' 
    }
    stages {
        stage ('Build') {
            steps {
                sh 'mvn clean deploy' 
            }
            post {
                success {
                    junit 'target/surefire-reports/**/*.xml' 
                }
            }
        }
    }
}
