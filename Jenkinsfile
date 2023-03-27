pipeline {
agent any 
  stages {
    stage('Build ec2') {
      steps {
        sh "aws cloudformation create-stack --stack-name laxmis3bucket --template-body file://s3bucket.json --region 'us-east-1'"
      }
    }
  }

}
