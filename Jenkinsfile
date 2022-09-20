pipeline {
    agent {
        label {
            label 'built-in'
        }
    }
    stages {
        stage ("git-clone"){
            steps{
                dir ("/mnt/clone/"){
            sh 'rm -rf *'
            sh 'git clone https://github.com/ragnar-git/newrepo.git'
                }
            }
            }
        }
    }

