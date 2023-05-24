pipeline { 
  
   agent any

   stages {
   
     stage('Install Dependencies') { 
        steps { 
           sh 'echo hii intsll dependency' 
        }
     }
     
     stage('Test') { 
        steps { 
           sh 'echo "testing application..."'
        }
      }

         stage("Deploy") { 
         steps { 
           sh 'echo "deploying application..."'
         }

     }
  
   	}

   }
