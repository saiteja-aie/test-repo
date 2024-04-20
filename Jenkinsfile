pipeline {
    agent {
        node { label 'BUILT_IN' }
    }

    options {
        timeout{time:5, unit:'MINUTES'}
    }

    stages {
        stage ('Initialize') {
            steps {
                echo 'Initializing the resouces.'
                sleep(10)
                echo 'Resouces has been initialized and ready for use.'
            }
        }
        stage ('Build') {
            steps {
                echo 'Building the run with the available data.'
                sleep(10)
                echo 'Created Build'
            }
        }
        stage ('Test') {
            steps {
                echo 'Testing the newly crated build run.'
                sleep(10)
                echo 'Build has been Verified'
            }
        }
        stage ('Deploy') {
            steps {
                echo 'Deploying the verified build.'
                sleep(10)
                echo 'Build has been Deployed'
            }
        }
    }
}