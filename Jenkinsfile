pipeline {
agent any 
  stages {
    stage('Build ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name ec2stacklaxmi1 --template-body file://ec2.yaml --region 'us-east-1'"
      }
    }
  }

}
