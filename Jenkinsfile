pipeline{
    agent {label 'ansible'}

    stages{
        stage('hello'){
            steps{
                sh '''
                    ansible --version
                    ansible-playbook --version
                    ansible 192.168.1.22 -m ping 
                '''
        }
        }
        
    }
}