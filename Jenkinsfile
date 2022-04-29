
node {
    stage('Clone') {
        git 'https://github.com/Meumo/mvn-helloworld.git'
	}
	 stage('Build') {
	     sh '''
	       cd /src/main/java &&  javac HelloWorld.java
		 '''
		 }
		  stage('Run') {
		      sh '''
		          cd /src/main/java && java HelloWorld
			  '''
			  }
			  }
