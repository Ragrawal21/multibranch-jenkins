pipeline{
  agent any
  stages{
    stage('Decleration'){
      steps{
        echo 'This is main branch'
      }
    }
    stage('Confirmation'){
      steps{
        sh 'mvn -v'
      }
    }
    stage('Owner'){
      steps{
        echo 'Configured by Rahul'
      }
    }
  }  
}
