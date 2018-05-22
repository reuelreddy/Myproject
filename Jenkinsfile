pipeline { 

	stage('Clone repository') {
        /* Let's make sure we have the repository cloned to our workspace */

        checkout scm
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

