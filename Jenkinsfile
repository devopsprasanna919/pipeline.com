pipeline {
    agent {
        label 'jenkinsslave'
    }
    tools {
        maven 'maven-3.8.9'
    }
    stages {
        stage ("maven") {
            steps {
                echo 'hello welocome to maven version'
                sh "mvn --version"
            }
        }
    }
}
