node {
    
    stage('maven version') {
	   sh 'mvn --version' 
	}
	stage('Java version') {
	   sh 'java --version' 
	}
	stage('git version') {
	    sh 'git --version'
    }
	stage('git clone') {
	    git credentialsId: 'pushpa', url: 'https://github.com/pushpa1998r/s-1234.git'
	}
	stage('maven Validate') {
	    sh 'mvn validate'
	}
	stage('maven test') {
	   sh 'mvn test'
	}
	stage('mvn compile') {
	   sh 'mvn compile'
    }
	stage('mvn package') {
	   sh 'mvn package'
    }
	
    
}