pipeline {

    agent {label 'Java'}
    stages {
        stage('test') { 
            steps {
              echo 'This is test2' 
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
