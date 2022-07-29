pipeline{
  agent any 
  stages {
    stage('Starting...'){
      steps {
        echo'Initialize'
      }
    }
    stage('Compile'){
      steps{
        bat 'javac Start.java'
        bat 'java Start'
      }
    }
  }
}
