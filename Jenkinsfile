node {
    
    stage('Clone') {
        git 'https://github.com/MarwenHHAMMAMI/jenkins-helloworld.git'
    }
    
    stage('Build') {
        sh label: '', script: 'javac Main.java'
    }
    
    stage('RUN') {
        sh label: '', script: 'java Main'
    }
    
}
