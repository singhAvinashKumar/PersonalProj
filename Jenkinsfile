pipeline{
  agent any
tools{
  maven 'Maven-3.9.5'
  jdk 'jdk17'
}
  stages{

    stage('Build'){
      steps{
        echo 'Build the project using Maven'
                bat 'mvn clean install -DskipTests'
        
      }
    }
  }
}
