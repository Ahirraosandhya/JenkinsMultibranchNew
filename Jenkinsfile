pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'npm install' 
        }
     }
     
     stage('Test1') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy node application") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
