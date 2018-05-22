pipeline { 
   agent {
	dockerfile true
   }
 

   stages {
	stage('Build') {
		 
		  app =  docker.build("reuelreddy/Myproject")
		}
	    
	stage('Test') {
		steps {
			echo 'testing....'
		}
	   }
	stage('Deploy') {
		steps {
			echo 'deploying....'
		}
	   }

	}
}
