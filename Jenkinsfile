
pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                echo "${env.gitBranch}".substring(gitBranch.indexOf('/')+1, gitBranch.length()).replace("/", "_")
            }
        }
    }
}