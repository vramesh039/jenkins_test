pipeline {
        agent any
        stages {
                stage('stage1') {
                        steps {
                               sh 'ls'
                        }
                }
        }
        post {
                success{
                        echo 'The command executed sucessfully'
                }
                failure {
                        echo 'This command was not executed sucessfully'
                }
        }
}

             
