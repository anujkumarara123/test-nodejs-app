pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           //sh 'npm install' 
          sh 'echo "installing deoendencies"'
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy nodejs application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
