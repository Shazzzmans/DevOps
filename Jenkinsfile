node('node1') {
    def mvnHome
    def javaHome
    stage('Preparation') { // for display purposes
        mvnHome = tool 'm3'
        javaHome = tool 'jdk8'
    }
    stage('Checkout') {
        git url:'https://github.com/Shazzzmans/DevOps.git', branch:'master'
    }
    stage('Compile') {
        sh 'echo "Hello World"'
        }
}
