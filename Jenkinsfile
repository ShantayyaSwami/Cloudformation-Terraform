pipeline {
    agent any
    stages {
        stage('Build VPC Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ConditionalVPC --template-body /var/lib/jenkins/Cloudformation/ConditionalVPC.yaml --region 'ap-south-1'"
              }
             }
            }
            }
