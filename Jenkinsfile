@Library('pipeline-library-demo')_

pipeline {
    agent {
	 label 'master'
		}
    stages {
        stage('Demo') {
            steps {
                
 			log.info "Starting"

  
			echo 'Hello World'
  
   
			log.warning "Saying hello to Dave"

  
			sayHello 'Dave'
  
  
			log.info "Completed"
            }
        }
}
