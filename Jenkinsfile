pipeline
{

agent any
   tools
    {
        maven 'maven'
    }
stages
{
   stage("checkoutcode")
    {
         steps
         {
             echo "welcome to multi-branchpipeine"
             git 'https://github.com/vesireddyramana/multibranch.git'
             echo "webhooks are configured successfully."
          }
     }

   stage("check")
   {
      
       steps
      {
          echo "welcome"
      }
   }

   stage("compile the code")
   {
       steps
      {
           sh 'mvn compile'
      }
    }
}
}
