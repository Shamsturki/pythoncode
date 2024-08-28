pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           echo "insatalling dependecnices and checking test" 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
