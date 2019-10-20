node {
    def hello = 'Hello World'
    stage ('clone') {
        git 'https://github.com/welearntocode/HelloWorld.git'
    }
    dir ('sh') {
        stage ('sh/execute') {
            sh './a.sh'
        }
    }
    stage ('print') {
        print(hello) 
    }
}

// void for no return
// def for return
void print(message) {
    echo "${message}"
}