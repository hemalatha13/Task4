properties([[$class: 'GithubProjectProperty',
            displayName: '', 
            projectUrlStr: 'https://github.com/hemalatha13/Task4.git/'], 
            pipelineTriggers([])])


pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post { 
        always { 
            echo 'I will always say Hello again!'
            echo 'I am task 5'
        }
    }
}
