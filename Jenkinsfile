pipeline {
    agent any
    triggers {
        githubPush()
    }
    stages {
        stage('Display Info') {
            steps {
                script {
                    echo "JENKINS_URL: ${env.JENKINS_URL}"
                    echo "BUILD_ID: ${env.BUILD_ID}"
                }
            }
        }
    }
}
