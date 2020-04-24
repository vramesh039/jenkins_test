adcd = ['a', 'b', 'c', 'd']

node ('master') {
        stage('testing loop') {
                echo_all(adcd)
        }
}

def echo_all(list) {
        for (int i = 0; i < list.size(); i++) {
        sh " echo This is ${list[i]}"
        }
}

                
