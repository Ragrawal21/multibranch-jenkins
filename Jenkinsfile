pipeline{
  agent any
  stages{
    stage('Decleration'){
      steps{
        echo 'This is main branch'
      }
    }
    tools{
      maven 'MAVEN 3.8.1'
    }
    stage('Confirmation'){
      steps{
        sh 'mvn -v'
      }
    }
    post{
      always{
        echo 'Configured by Rahul'
      }
    }
  }  
}
