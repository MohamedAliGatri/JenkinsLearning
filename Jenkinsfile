def gv
pipeline{
    agent any
    tools{
        maven "MAVEN_HOME"
    }
    stages{
        stage("Git checkOut"){
            gv = load "script.groovy"
        }
    }
}