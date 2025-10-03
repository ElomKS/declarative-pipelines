pipeline {

    agent any

    stages {
        stage ('SCM'){
            steps {
               git branch: 'main', url: 'https://github.com/ElomKS/declarative-pipelines.git'
            }
        }
    }
}