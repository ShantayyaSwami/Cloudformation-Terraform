pipeline {
    agent any
    stages {
        stage('BuildVPCStack') {
            steps {
            sh "aws cloudformation create-stack --stack-name ConditionalVPC --template-body file://ConditionalVPC.yaml --region 'ap-south-1' --parameters Parameterkey=Tenancy, ParameterVlue=dedicated"
              }
             }
            }
            }
