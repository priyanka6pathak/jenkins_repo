pipeline{

    agent any
     
    stages {
        
      stage("build") {
        
         steps {
          
               echo 'building the application ....'
             echo 'build is done'
         }
      }

      stage("test") {
         
        steps {
          
              echo 'testing the application ....'
              echo 'test is done ....'
        }
       
      }
      
       stage("deploy") {
         
        steps {
          
               echo 'deploying the application ....'
        }
       
      }

    }
}
