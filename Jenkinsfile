pipeline {
    agent any
    stages {
        stage('****Install Apache****') {
            steps {
                sh 'ansible-playbook -i Inventory/Apache-Installation playbooks/ansible_playbook.yml'
            }
            println('Installing Apache Completed!')
        }
    }
}
