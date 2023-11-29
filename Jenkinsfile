pipeline {
    agent any 
    stages{
        stage('clone'){
           steps{
            git 'https://github.com/Premchand-1/Maven_Build.git'
           }
        }
         stage('build'){
           steps{
            sh "mvn clean install"
           }
        }
    
    }
}
