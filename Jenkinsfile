pipeline { 
    agent any  
    stages { 
        stage('Build') { 
            steps { 
                sh '''
               cd /mnt/c/Users/hasher/Documents/maven/maven-e1
               mvn clean install
               echo 'worked'
               ''' 
            }
        }
    }
}