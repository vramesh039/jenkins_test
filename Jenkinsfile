pipeline {
        agent any
        
        options {
                timestamps()
                ansiColor("xterm")
        }
        
        stages {
                stage("step1") {
                        options {
                                timeout(time: 1, unit: "MINUTES")
                        }
                        steps {
                                sh 'printf "executing step1'
                        }
                }
                stage("step2") {
                        options {
                                timeout(time: 2, unit: "MINUTES")
                        }
                        steps {
                                sh 'printf "executing step2'
                        }
                }
        }
}
                   
                                
                        
