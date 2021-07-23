node {
    stage('clean') {
        sh 'rm -fr *'
    }
    stage('clone') {
        sh "git clone https://github.com/zensix/TestJavaSimple.git"
    }
    stage('build') {
        sh 'cd TestJavaSimple/ && javac Main.java'
    }
    stage('run') {
        sh 'cd TestJavaSimple/ && java Main'
    }
}
