def gv
pipeline{
    agent any
    tools{
        maven "MAVEN_HOME"
    }
    stages{
        stage("Git checkOut"){
            steps{
                script{
                    gv = load "script.groovy"
                }
            }
        }
    }
}