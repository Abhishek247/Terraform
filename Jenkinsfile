pipeline {
    agent any 
    stages {
        stage('Initiate') { 
            steps {
                sh "Terraform init"
            }
        }
        stage('Plan') { 
            steps {
                sh "Terraform Plan" 
            }
        }
        stage('Apply') { 
            steps {
                sh "Terraform Apply"
            }
        }
    }
}
