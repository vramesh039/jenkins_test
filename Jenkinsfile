adcd = ['a', 'b', 'c', 'd']

node ('master') {
        stage('testing loop') {
                echo_all(adcd)
        }
}

def echo_all(list) {
        list.each { item ->
                echo "This is ${item}"
        }
}
                
