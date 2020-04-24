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
                sucess{
                        echo 'The command executed sucessfully'
                }
                failure {
                        echo 'This command was not executed sucessfully'
                }
        }
}

             
