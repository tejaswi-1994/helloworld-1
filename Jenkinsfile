pipeline {
    agent  any  
    stages {
        stage('building from pipeline script') {
            steps {
                sh 'lsblk'
		sh 'pwd'
		sh 'lscpu'
		sh 'ping -n 4 google.com'
            }
        }
    }
}
