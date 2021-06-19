pipeline { 
    agent none 
    stages {
        stage('Build') { 
         agent {
             label 'master'
         }
            steps { 
                echo 'first build' 
            }
        }
        stage('Test'){
         agent {
             label 'node1'
         }
            steps {
                echo 'first test' 
            }
        }
        stage('Deploy') {
         agent {
             label 'node1'
         }
            steps {
                echo 'first deploy'
            }
        }
    }
}
