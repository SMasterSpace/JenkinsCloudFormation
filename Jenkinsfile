pipeline {
    agent any
    stage ('Maven'){
     sh "mvn clean package"
    }    
    stage ('Deploy'){
     sh "mvn deploy"
    }
}
