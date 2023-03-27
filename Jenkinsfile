pipeline {
agent any 
  stages {
    stage('Build ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmiec2groupstack2 --template-body file://laxmi-ec2.yaml --region 'us-east-1'"
      }
    }
  }

}
