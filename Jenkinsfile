pipeline {
    agent any
    tools {
        maven 'maven_autoinstaller'
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
