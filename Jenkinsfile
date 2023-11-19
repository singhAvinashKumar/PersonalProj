pipeline{
  agent any
tools{
  maven 'Maven-3.9.5'
  jdk 'jdk17'
}
  stages{
    stage('Git_Checkout'){
      steps{
      echo 'Checkout code from Git'
                git 'https://github.com/singhAvinashKumar/PersonalProj.git'
      }
    }
    stage('Build'){
      steps{
        echo 'Build the project using Maven'
                bat 'mvn clean install -DskipTests'
        
      }
    }
  }
}
