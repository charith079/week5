pipeline{
  agent any
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
          script{
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
