pipeline{
    agent any

    stages{
        stage('hello'){
            steps{
                sh '''
                    ansible --version
                    ansible-playbook --version
                '''
        }
        }
        
    }
}