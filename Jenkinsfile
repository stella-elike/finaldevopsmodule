pipeline{
  agent any
  stages{
    stage ('Deploy'){
      steps{
        echo "Test Succesful"
        bat "mvn compile"
      }
    }
    stage ('Build'){
      steps{
        echo "Build Successful"
        bat "mvn clean"
      }
    }
    stage ('Test'){
      steps{
        echo "Test Successful"
        bat "mvn test"
      }
    }
  }
}
      
