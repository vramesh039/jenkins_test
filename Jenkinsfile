pipeline {
        agent any
        stages {
                stage('devmaster') {
                        when {
                                anyOf {
                                        branch 'master'; branch 'development'
                                }
                        }
                                    
                        steps {
                               echo 'I am either mater or development branch'
                        }
                }
                stage('master') {
                        when {
                                branch 'master'
                        }
                        steps {
                                echo 'I am master'
                        }
                }
        }
}
