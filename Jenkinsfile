pipeline {
    agent {
        docker { image 'node:22.21.0-alpine3.22' }
    }
    stages {
        stage('Test') {
            steps {
                node --eval "console.log(process.arch,process.platform)"
            }
        }
    }
}
