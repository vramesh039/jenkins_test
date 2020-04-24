node {
        timestamps {
                ansiColor("xterm") {
                        stage("stage1") {
                                timeout(time: 1, unit: "MINUTES") {
                                        sh 'printf "\\e[31mexecuting step1\\e[0m\\n"'
                                }
                        }
                        if (env.state == "test") {
                        stage("stage1") {
                                timeout(time: 2, unit: "MINUTES") {
                                        sh 'printf "\\e[31mexecuting step2\\e[0m\\n"'
                                }
                        }
                        }
                }
        }
}
