pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'Hello World'
            }
        }
        stage('test') {
            steps {
                echo 'Hello World'
            }
        }
        stage('deploy') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post
    {
        always
        {
            emailext body: 'body', subject: 'bodypipeline', to:'mounikagarimella618@gmail.com'
        }
    }
}
