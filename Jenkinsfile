pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'running build automation'
                ansiblePlaybook('/etc/ansible/switch_configs.yml') (
                    inventoryPath('/etc/ansible/hosts')
                    ansibleName('2.8.1')
                    }
                }
            }
        }    
