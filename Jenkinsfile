properties([
  pipelineTriggers([
    upstream(
      threshold: 'SUCCESS',
      upstreamProjects: '../Jenkinsfile/master'
    )
  ])
])

pipeline {
    agent any
    stages {
        stage('Example') {
            steps {
                echo 'Hello hema'
            }
        }
    }
    post { 
        always { 
            echo 'I will always      say Hello again!'
        }
    }
}
