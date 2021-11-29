pipeline{
  agent any
  
  stages{
    
    stage('install'){
      steps{
        git 'https://github.com/shambhu1977/Hi.git'
      }
    }
    
    stage('Run hi'){
      steps{
        bat 'python3 hi.py'
      }
    }
  }
}
