node {
    stage('clone') {
        sh "git clone https://github.com/zensix/TestJavaSimple.git"
    }
    stage('build') {
        sh label:'', script: 'javac Main.java'
    }
    stage('run') {
        sh label:'', script: 'java Main'
    }
}
