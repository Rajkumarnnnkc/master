pipeline {
def readProb;
def FAILED_STAGE
agent { label 'master'}
stages {
  stage('Git Pull'){
        steps {	dir("${readProb['Project_name']}"){
		 git branch: "${readProb['branch']}", credentialsId: "${readProb['username']}", url: "${readProb['git.url']}"    
	      }
		}
  }
}
