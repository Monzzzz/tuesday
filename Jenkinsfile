pipeline{
  agent any 
  stages {
    stage('Starting...'){
      steps {
        echo'Starting'
      }
    }
    stage('Compiling'){
      steps {
        bat '\tools\jdk\bin\java.exe Start.java'
      }
    }
    stage('Testing'){
      steps{
        bat '\tools\jdk\bin\java.exe Start'
      }
    }
  }
}
