pipeline {
  
  agent any
  environment {
      NEW_VERSION = '1.3.0'
  
  stages {
    
      stage ("Build") {
      
         steps {
            echo 'building the applicaton...'
            echo "buildind ${NEW_VERSION}"
        
      }
    }
          
       stage ("Test") {
      
          steps {
             echo  'testing the application...'
        
      }
    }
        stage ("Deploy") {
      
           steps {   
             echo 'deploying the application..'
        
      }
     }
  }
}
    
