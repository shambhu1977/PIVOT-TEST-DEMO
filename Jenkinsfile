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
        bat '''@echo off
        "C:\\Python310\\python.exe" "https://github.com/shambhu1977/Hi/blob/master/hi.py"
        pause'''
      }
    }
  }
}
