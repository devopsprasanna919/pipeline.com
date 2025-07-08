pipeline {
    agent {
        label 'jenkinsslave'
    }
    tools {
        maven 'maven-version'
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
