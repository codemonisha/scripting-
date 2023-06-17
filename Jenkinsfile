
pipeline {
    agent any 
    parameters {

        string(name: 'num1', defaultValue: ' ' )
        string(name: 'num2', defaultValue: ' ' )

       
    }
    
    stages {
        stage('checkout') {
            steps {
                 
                   sh 'sh calcu.sh'
            }
        }
    }
}








