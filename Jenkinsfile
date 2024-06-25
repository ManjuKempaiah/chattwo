pipeline{
  agent any
  stages{
    stage('Jenkins File'){
      steps{
        echo "This is Jenkins File demo"
      }
    }
    stage('Dev Deploy'){
      when{
        branch 'develop'
      }
      steps{
        echo 'deploying to develop'
      }
    }
    stage('Test Deploy'){
      when{
        branch 'test'
      }
      steps{
        echo 'deploying to test'
      }
    }
    stage('Prod Deploy'){
      when{
        branch 'main'
      }
      steps{
        echo 'deploying to prod'
      }
    }
  }
}
