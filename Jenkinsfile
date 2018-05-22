pipeline { 
   agent {
	dockerfile true
   }

	stage('Build image') {
        /* This builds the actual image; synonymous to
         * docker build on the command line */

        app = docker.build("reuelreddy/Myproject")
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

