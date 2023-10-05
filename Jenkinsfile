pipeline { 
agent any
    stages {
        stage('Build') {
            steps {
                echo 'This is job building stage'
            }
        }
        stage('Test') {
            steps {
                 echo 'This is Testing stage'
            }
        }
     stage('Staging') {
            steps {
                echo 'This is Staging environment'
            }
        }
     stage('Deploy') {
            steps {
                echo 'This is Deploying stage'
            }
        }
      stage('Monitor') {
            steps {
                echo 'This is Monitoring stage'
            }
        }
    } 
}
