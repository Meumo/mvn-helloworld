
node {
    stage('Clone') {
        git 'https://github.com/Meumo/mvn-helloworld.git'
	}
	 stage('Build') {
	     sh '''
	         javac Main.java
		 '''
		 }
		  stage('Run') {
		      sh '''
		          java Main
			  '''
			  }
			  }
