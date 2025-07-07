pipeline {
    agent {
        label "jenkinsslave"
    }
    stages {
        stage ("maven") {
            steps {
                echo ('hello welocome to maven version')
                sh "mvn --version"
            }
        }
    }
}
