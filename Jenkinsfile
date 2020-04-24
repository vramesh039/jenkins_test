pipeline {
        agent any
        parameters {
                string( name: 'NAME', defaultValue: 'jenkinstraining', decsription: 'please enter your name')
                
                text( name: 'BIO', defaultValue: '', decsription: 'please say something about you')
                
                choice( name: 'CHOICE', choices:  ['one', 'two', 'three'], decsription: 'please chose one')
                
                booleanParam( name: 'BOOLEAN', defaultValue: true, decsription: 'please select boolean value')
                
                password( name: 'PASSWORD', defaultvalue: 'test123', decsription: 'please enter password')
        }
        
        stages {
                stage('print values') {
                        steps {
                                echo "Hello ${params.NAME}"
                                echo "Your Biography: ${params.BIO}"
                                echo "Your choice is: ${params.CHOICE}"
                                echo "Your boolean choice is: ${params.BOOLEAN}"
                                echo "your password is: ${params.PASSWORD}"
                        }
                }
        }
}
                
