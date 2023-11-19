pipeline{
  agent any
tools{
  maven ' Maven 3.9.5'
}
  stages{
    stage('Git_Checkout'){
      echo 'Checkout code from Git'
                git 'https://your.git.repo.url.git'
    }
    stage('Build'){
      steps{
        echo 'Build the project using Maven'
                sh 'mvn clean install'
        
      }
    }
  }
}
