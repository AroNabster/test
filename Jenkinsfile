
pipeline { 
    agent any 
    stages {
        stage('Build') { 
            steps { 
                echo "${env.gitBranch}".replace("/", "_")
            }
        }
    }
}