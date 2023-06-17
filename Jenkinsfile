
pipeline {
    agent any 
    parameters {

        string(name: 'name', defaultValue: ' ' )
        string(name: 'place', defaultValue: ' ' )
       
    }
    
    stages {
        stage('checkout') {
            steps {
                 
                   sh 'sh para.sh'
            }
        }
    }
}








