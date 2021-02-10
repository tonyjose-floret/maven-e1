pipeline {
    agent any
    tools { 
        maven 'Apache Maven 3.6.0' 
        jdk 'openjdk 11.0.9.1' 
    }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }

        stage ('Build') {
            steps {
                echo 'This is a minimal pipeline.'
            }
        }
    }
}