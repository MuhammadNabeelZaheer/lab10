pipeline {

    agent any
    
    stages {
        stage('checkout') {
          steps {
              bat 'npm install'
            }
          }
        
        stage('dependency') {
          steps {
              bat 'npm install'
            }
          }
        
         stage('build') {
          steps {
              bat 'npm install'
            }
          }
        
        stage('test') {
          steps {
              bat 'npm install'
            }
          }
        stage('Docker Compose Up') {
            steps {
               
                    bat "docker compose up"
                
            }
        }
    }
}
