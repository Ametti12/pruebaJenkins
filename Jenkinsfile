pipeline {
    agent any
    
    tools{
        maven "maven-nodo-principal"
    }

    stages {
        stage('Build') {
            steps {
                dir (‘maven-adderapp’) {
                    
                    writeFile file:'dummy', text:''
                                        
                    sh 'mvn -DskipTests clean package'
                }     
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
