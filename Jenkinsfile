pipeline {
agent { label 'master'}
stages {
  stage('Git Pull'){
        steps {	dir("${readProb['Project_name']}"){
		 git branch: "${readProb['branch']}", credentialsId: "${readProb['credentials']}", url: "${readProb['git.url']}"    
	      }
		}
  }
