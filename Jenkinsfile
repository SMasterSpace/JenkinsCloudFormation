pipeline {
    agent any
    
    //stage('git'){
    //git credentialsId: 'git-creds', url:'https://github.com/SMasterSpace/JenkinsCloudFormation.git'        
    //}
    
    stage ('Maven'){
     sh "mvn clean package"
    }
    
    stage ('Deploy'){
     sh "mvn deploy"
    }
}
