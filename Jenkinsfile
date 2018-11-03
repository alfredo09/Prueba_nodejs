pipeline 
{
  agent any
 
  tools {
	nodejs “nodejs-1”
	}
 
  stages 
  {
    stage(‘Example’) 
    {
      steps 
      {
        sh ‘npm config ls’
      }
    }
      stage(‘version’) 
      {
      steps 
       {
        sh ‘node --version’
       }
      }
   }
}
