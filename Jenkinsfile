pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'echo "Hello Universe"'
                sh 'php --version'
            }
        }
        post {
            always {
              echo 'This should run always'
            }
        }
    }
}
