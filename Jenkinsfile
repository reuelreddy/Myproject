pipeline { 
   agent {
	dockerfile true
   }
 

   stages {
	stage('Build') {
		steps {
		    docker.build("reuelreddy/Myproject")
		}
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
