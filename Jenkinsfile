node('master')

{

stage('ContinuousDownload_loans') 
   
	 {
	
    git 'https://github.com/parkerOnGithub/maven-test.git'
    
	}

stage('Continuousbuild_loans') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}

}

