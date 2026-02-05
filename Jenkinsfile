pipeline {
    agent any
    stages { stage('Work') { steps { echo 'Doing work...' } } }
    post {
        success { echo 'HOORAY! It worked.' }
        failure { echo 'OH NO! It failed.' }
    }
}
