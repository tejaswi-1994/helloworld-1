pipeline {
    agent  any  
    stages {
        stage('building from pipeline script') {
            steps {
                sh 'lsblk'
		sh 'pwd'
		sh 'lscpu'
		sh 'ping -c 4 google.com'
            }
        }
    }
}
