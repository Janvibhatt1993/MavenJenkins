pipeline {
    agent any
    stages{
        stage('Git clone'){
            steps {
                git branch: 'main', url: 'https://github.com/Janvibhatt1993/MavenJenkins.git'
            }
        }
        stage('Maven Test'){
            steps {
                bat 'mvn test'
            }
        }
        stage('Maven Build'){
            steps {
                bat 'mvn package'
            }
        }
        stage('Maven Deploy'){
             steps{
                echo "Hi Team" 
             }
            }
    }
}
