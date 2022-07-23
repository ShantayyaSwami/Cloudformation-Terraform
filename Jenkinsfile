pipeline {
    agent any
    stages {
        stage('Build VPC Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ConditionalVPC --template-body file://ConditionalVPC.yaml --region 'ap-south-1' --parameters 'Parameterkey=Tenancy,ParameterValue=dedicated'"
              }
             }
            }
            }
