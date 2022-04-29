
node {
    stage('Clone') {
        git 'https://github.com/Meumo/mvn-helloworld.git'
	}
	 stage('Build') {
	     sh '''
	       javac HelloWorld.java
		 '''
		 }
		  stage('Run') {
		      sh '''
		          java HelloWorld
			  '''
			  }
			  }
