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
        sh 'python3 hi.py'
      }
    }
  }
}
