pipeline {
    agent any;
  stages {

    stage ('BUILD') {
      steps {
        echo "This is Build stage" 
        sh ''' echo $BUILD_NUMBER
               echo $BUILD_ID  
           '''
     
      }  
    }  
    
    stage ('TEST') {
      steps {
        echo "This is Test stage" 
        
      }  
    }  
    
    stage ('DEPLOY') {
        steps {
             echo "This is Deploy stage" 
             sh 'sleep 5'
        }
   }
        
  }

}
  
