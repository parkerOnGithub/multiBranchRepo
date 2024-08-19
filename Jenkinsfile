node('master')

{

stage('ContinuousDownload_master') 
   
	 {
	
    git 'https://github.com/parkerOnGithub/multiBranchRepo.git'
    
	}

stage('Continuousbuild_master') 
   
	 {
	
   sh label: '', script: 'mvn package'
	}
}

