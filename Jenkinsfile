pipeline {

    agent any
    stages {
        stage('Build') {
           steps{
            echo 'Hi Jay'
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