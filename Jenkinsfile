pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
          // sh 'npm install'
          sh 'echo "testing application..."'
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
