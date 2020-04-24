pipeline {
        agent any
        stages {
                stage('input') {
                        input {
                                message "IS It ok to deploy the code on production"
                                ok "Yes"
                                submitter "admin"
                                parameters {
                                        string(name: 'USER', defaultValue: 'admin', description: 'administrator')
                                }
                        }
                        steps {
                                echo "${USER} approved, proceeding with prodution deployment"
                        }
                }
        }
}
                                
