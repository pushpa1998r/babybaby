node {
    
    stage ('maven version') {
	   sh 'mvn --version' 
	}
	stage ('Java version') {
	   sh 'java --version' 
	}
	stage ('git version') {
	    sh 'git --version'
    }
	stage ('git clone') {
	    git credentialsId: 'pushpa', url: 'https://github.com/kartikeyapro/app.git'
	}
	stage ('Maven Package') {
	    sh 'mvn --package'
    }
	
    
}