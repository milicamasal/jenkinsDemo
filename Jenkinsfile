pipeline{

  agent { 
    docker { image 'python:3.7.2' } }
  
    stages{
       stage("new") {
       steps{
          echo 'neww the application'
        }
      }
      stage("build") {
        steps{
          echo 'building the application'
      
        }
      }
      stage("test") {
        steps{
          echo 'testing the application'
        }
      }
    }
}
