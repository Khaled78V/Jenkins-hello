node {
    stage('Clone') {
        git 'https://github.com/Khaled78V/Jenkins-hello.git'
    }
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    stage('Run') {
        sh label: '', script: 'java Main'
    }
}
