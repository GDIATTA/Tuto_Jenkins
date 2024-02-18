 agent { 
        node {
            label 'docker-agent-python'
            }
    }
    stages {
        stage('Build') {
            steps {
                echo 'Hello World'
                sh '''
                python3 app.py
                '''
            }
        }
    }
}
