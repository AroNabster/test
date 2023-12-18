
pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                echo "${env.gitBranch}".substring(env.gitBranch.indexOf('/')+1).replace("/", "_")
            }
        }
    }
}