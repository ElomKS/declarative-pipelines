pipeline {
    agent any

    triggers{
        cron('0 3 * * 1-5')
    }
    stages {
        stage ('SCM'){
            steps {
               git branch: 'main', url: 'https://github.com/ElomKS/declarative-pipelines.git'
            }
        }
        stage ('build'){
            steps {
                echo 'Build in process'
               //
            }
        }
    }
}