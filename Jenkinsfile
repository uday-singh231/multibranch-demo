node {
    stage ('scm checkout'){
        git credentialsid: 'GSB-Demo', url: 'https://github.com/uday-singh231/multibranch-demo.git'
    }
    stage ('shell exec') {
        sh 'echo "Hello World'
    }
}
