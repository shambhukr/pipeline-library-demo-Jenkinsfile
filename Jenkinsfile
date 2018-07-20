@Library('pipeline-library-demo')_

pipeline {
    agent {
	 label 'master'
		}
	
	environment{
		lastmessage = log.returnStr "finally"	
		
	}
    stages {
        stage('Demo') {
            steps {
		    echo env.lastmessage
		    
		    script{
 			log.info "Starting"

  
			echo 'Hello World'
  
   
			log.warning "Saying hello to Dave"

  
			sayHello 'Dave'
  
  
			log.info "Completed"
			echo "${env.lastmessage}"        
		    }    
            }
        }
	}
}
