node {
    stage('Checkout') {
        checkout scm
    }
    stage('Build Docker image') {
        sh "docker build -t mypromille-firebase-tools:latest ."
    }
}
