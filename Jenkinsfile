pipeline {

    agent any
    stages {
        stage('test') { 
            steps {
              echo 'This is test' 
            }
        }
        
        stage('Build') { 
            steps {
              sh 'mvn clean package' 
            }
        }


    } 
    
    post {
        always { 
            echo 'I will always say Hello again!'
        }
         success { 
            echo 'I will always say Hello again!'
        }
    }



}
