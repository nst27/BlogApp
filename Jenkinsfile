pipeline{
  agent any
  tools {nodejs "node"}
  
  stages{
    stage("Hello"){
      steps{
        echo "npm install"
      }
    }
    stage('Deploy'){
      steps{
        sh "npm start"
      }
    }
  }

}
