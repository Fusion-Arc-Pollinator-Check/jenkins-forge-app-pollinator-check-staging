
   
pipeline {
    agent  any
    stages {
        stage('deployments') {
            parallel {
                stage('deploy to prod') {
                    steps {
                        echo 'prod deployment done'
                    }
                }
            }
        }
    }
}
