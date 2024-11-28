pipeline{
  agent any
  {
    stages{
      stage('Build'){
        steps{
          script{
            bat 'docker build -t week5 .'
          }
        }
      }
      stage('Test'){
        steps{
          scrit{
            echo 'testing tests'
          }
        }
      }
      stage('Deploy'){
        script
        {
          echo 'Deploying'
        }
      }
    }
  }
}
