
node {
    stage('Clone') {
        git 'https://github.com/Meumo/mvn-helloworld.git'
	}
	 stage('Build') {
	     sh '''
	       cd /src/main/java &&  javac Main.java
		 '''
		 }
		  stage('Run') {
		      sh '''
		          cd /src/main/java && java Main
			  '''
			  }
			  }
