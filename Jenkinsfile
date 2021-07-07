pipeline
{
   agent any
   tools {
        maven 'maven' 
    }
  stages{
    stage('Build')
    {
      steps{
         echo "Building....."
         sh 'mvn clean install'
        sh 'mvn --version'
      
        }
    
    }
  
  
  
  
  }
  


}
