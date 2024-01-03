node {
    stage('Build ng image') {
        stage('Pull repository') {
                checkout scm
            }
        stage('Clear Files') {
                sh 'rm -rf /var/www/html/*'
            }
            stage('Install npm') {
                sh 'cp index.html /var/www/html/index.html'
            }
    }
}
