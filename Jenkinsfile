pipeline{
	agent{
	     docker{
		image 'maven:3-alpine'
		args '-v /root/.m2/root/.m2'

	    }
	}
	stages {
		stage('Build"){
			stags{
				sh 'mvn -B _DskipTests clean package'			
			}		
		}	
	}
}
