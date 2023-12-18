
pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                echo "${env.gitBranch}".substring(branch.indexOf('/')+1).replace("/", "_")
            }
        }
    }
}