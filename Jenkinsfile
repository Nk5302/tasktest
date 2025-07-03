pipeline {
    agent any
    tools {
        maven 'maven'
    }
    stages {
        stage("pull the src") {
            steps {
                git branch: 'main',url: 'https://github.com/Nk5302/tasktest.git'
            }
        }
    }
}
