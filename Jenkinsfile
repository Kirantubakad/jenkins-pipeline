pipeline {
    agent any;
  stages {

    stage ('BUILD') {
      steps {
        echo "This is Build stage" 
        
      }  
    }  
    
    stage ('TEST') {
      steps {
        echo "This is Test stage" 
        
      }  
    }  
    
    stage ('DEPLOY') {
      steps {  
      
       stage ('server1') {
            steps {
                    echo "This is Deploy stage" 
                    sh 'sleep 5'
            }
       }
       stage ('server2') {
            steps {
                    echo "This is Deploy stage" 
                    sh 'sleep 5'
            }
       }
       stage ('server3') {
            steps {
                    echo "This is Deploy stage" 
                    sh 'sleep 5'
            }
       }
      }    
    } 
  } 

}
  
