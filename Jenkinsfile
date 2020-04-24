pipeline {
        agent any
        stages {
                stage('stage1') {
                        steps {
                               sh 'test'
                        }
                }
        }
        post {
                failure {
                        echo 'This is post build step'
                }
        }
}

             
