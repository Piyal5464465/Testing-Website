pipeline {
    agent any

    stages {
        stage('Deploy html site') {
            steps {
                publishHTML([allowMissing: false, alwaysLinkToLastBuild: false, keepAll: false, reportDir: '', reportFiles: 'blog.html', reportName: 'HTML Report', reportTitles: '', useWrapperFileDirectly: true])            }        }
    }
}
