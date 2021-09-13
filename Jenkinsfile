pipeline {
    agent any
    
    tools{
        maven "Maven-nodo-principal"
    }

    stages {
        stage('Build') {
            steps {
                echo 'Building..'     
            }
        }
            
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
    
}
