pipeline {
    agent {
        label 'jenkinsslave'
    }
    stages{
        stage ('build') {
            steps{
                timeout (time:5, unit:'SECONDS') {
                }
                echo " sleep for 30 seconds****"
                sleep 30
            }
            
        }
    }
}
