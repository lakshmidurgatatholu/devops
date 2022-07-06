pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello build env'
            }
        }
        stage('test') {
            steps {
                echo 'Hello test env'
            }
        } 
        stage('deploy') {
            steps {
                echo 'Hello deploy env'
            }
        }  
       stage('prod') {
            steps {
                echo 'Hello prod env'
            }
       }
      stage('monitor') {
            step {
                echo 'Hello mon env'
            }
        }    
    }
}
