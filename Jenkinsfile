pipeline {
    agent any
    stages {
        stage('****Install Apache****') {
            steps {
                sh 'ansible-playbook -i inventory.ini -b install_apache.yml'
            }
            prinltn('Installing Apache Completed!')
        }
    }
}
