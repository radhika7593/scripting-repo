pipeline {
    agent any

    stages {
        stage('Cloning the git repo') {
            steps {
                git credentialsId: 'git-credentails', url: 'https://github.com/radhika7593/scripting-repo.git'
            }
        }
        
        stage('Checking whether server is reachable or not') {
            steps {
                echo 'I am Radhika'
            }
        }
    }
}
