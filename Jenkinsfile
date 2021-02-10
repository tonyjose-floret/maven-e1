pipeline {
    agent any
    tools { 
        maven 'maven' 
        jdk 'jdk' 
    }
    stages {
        stage ('Initialize') {
            steps {
                sh '''
                    export M2_HOME=/usr/local/apache-maven
                    export M2=$M2_HOME/bin 
                    export PATH=$M2:$PATH
                    echo "PATH = ${PATH}"
                    echo "M2_HOME = ${M2_HOME}"
                ''' 
            }
        }

        stage ('Build') {
            steps {
                sh '''
                    cd /mnt/c/Users/hasher/Documents/maven/maven-e1
                    mvn clean install
                '''
            }
        }
    }
}