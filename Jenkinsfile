pipeline {
    agent any 
    stages {
        stage('Git Checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Percy-1031/spring-petclinic.git'
 
            }
        }
        stage("Maven Build"){
            steps{
                sh "mvn clean package"
            }
        }
    }
}