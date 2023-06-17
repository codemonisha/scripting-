
pipeline {
    agent any 
    parameters {

        string(name: 'name', defaultValue: 'enter name ' )
       
    }
    
    stages {
        stage('checkout') {
            steps {
                   sh 'hi ${name} , welcome to jenkins'
            }
        }
    }
}








