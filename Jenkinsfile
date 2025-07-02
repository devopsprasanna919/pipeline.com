pipeline {
    agent any
    stages {
        stage ('build') {
            steps {
                echo "** coming from github repo"
            }
        }
        stage ('groovystage') {
            steps{
                script{
                   // i want to define variable
                // def variablename = "value"
                defcourse ="k8s"
                println("Thanks for enrolling {course} course")
            }

            }
        } 
        
    }
}

// ${coures}, ${env.course}, ${params.course}
