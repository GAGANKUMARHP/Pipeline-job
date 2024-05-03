pipeline
{
agent {
  label 'newnode1'
}
 stages {
  stage('build') {
    steps {
      echo " new code for build"
      sh 'sleep 5'
    }
  }
  stage('test') {
    steps {
      echo "test caes to be reviwed"
       sh 'sleep 5'
    }
  }
  stage('deploy') {
    steps {
      echo " new build to deploy to QA"
       sh 'sleep 5'
    }
  }

}

  
  
  }

