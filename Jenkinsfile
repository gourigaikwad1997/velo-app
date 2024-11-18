pipeline {
	agent {
		label{
				label "built-in"
				customWorkspace "/data/pipeline"
		
		}
	}
	
	stages {
			stage ('one') {
					steps {
							 sh "echo 'Hello all' > qa.html"
					}
			}
			
			stage ('two') {
					steps {
					dir ('/data/pipeline/qa'){
							 sh "echo 'Hello all' > uat.html"
							 
							 }
					}
			}
			
	
	}

}
