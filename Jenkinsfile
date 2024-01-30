pipeline {
  
  agent any

  stages {
    
    stage("build") {
      
      steps {
        
        echo 'building the application'
        
      }
      
    }
    
    stage("test") {
      
      steps {
        
        echo 'testing the application'
        
      }
      
    }

    stage("deploy") {
      
      steps {
        
        echo 'deploying the application'
        
      }
      
    }

    stage("parallel") {
      
      parallel {
        
        stage('Unit Test') {
          
          steps {
            
            echo "Running the unit test..."
            
          }
          
        }
        
        stage('Integration test') {
          
          steps {
            
            echo "Running the integration test..."
            
          }
          
        }
        
      }
      
    }
    
  }
  
}
