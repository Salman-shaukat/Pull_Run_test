pipeline {
    agent any

    stages {
        stage('Clear_Workspace') {
            steps {
                cleanWs()
            }
        }
        stage('Git_Pull') {
            steps {
                git branch: 'main', url: 'https://github.com/carlosalexei/demoapps.git'
            }
        }
        stage('Build') {
            steps {
                echo 'Need to look into how to build a .NET project!!'
            }
        }
    }
}
