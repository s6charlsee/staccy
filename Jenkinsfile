pipeline {
    agent any
    options {
     buildDiscarder logRotator(artifactDaysToKeepStr: '', artifactNumToKeepStr: '', daysToKeepStr: '4', numToKeepStr: '2')
     disableConcurrentBuilds()
    }

    stages {
        stage('create a directories') {
            steps {
                sh '''
                mkdir cha
                rm -rf cha
                '''
                
            }
        }


        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
    }
}
