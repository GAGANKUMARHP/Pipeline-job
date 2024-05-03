pipeline
{
agent none
 stages {
  stage('build') {
    agent any
    steps {
      echo " new code for build"
      sh 'sleep 5'
    }
  }
  stage('test') {
    agent { label 'newnode1'}
    steps {
      echo "test caes to be reviwed"
       sh 'sleep 5'
    }
  }
  stage('deploy') {
    agent { label 'master'}
    steps {
      echo " new build to deploy to QA"
       sh 'sleep 5'
    }
  }

}

  
  
  }

