
pipeline {
    agent any 
    parameters {

        string(name: 'name', defaultValue: 'enter name ' )
        string(name: 'place ', defaultValue: 'enter place ' )
    }
    
    stages {
        stage('checkout') {
            steps {
                   sh 'hi ${name} , welcome to ${place} '
            }
        }
    }
}








