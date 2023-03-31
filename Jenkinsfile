pipeline {
agent any 
  stages {
    stage('Build Repo') {
      steps {
        sh "aws cloudformation create-stack --stack-name KhadijehEc2Stack1 --template-body file://ec2instance.yaml --region 'us-east-1'"
      }
    }
  }

}
