pipeline {
agent {
  label 'LinuxSlave_ssh'
}

    stages {
        
       
        
        stage('Build') {
            steps {
                sh label: '', script: './gradlew build'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploy..'
            }
        }
    }
}
