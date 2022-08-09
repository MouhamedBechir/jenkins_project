pipeline{
    agent any

    stages('Hello'){
        steps{
            sh '''
                ansible --version
                ansible-playbook --version

            '''
        }
    }
}