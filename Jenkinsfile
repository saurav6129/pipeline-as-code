pipeline {
	
	agent any
	
	stages {
		
		stage("build") {
			
			steps {
				echo 'building the application...'
			
			 }
		 }
		stage("test") {
<<<<<<< HEAD
=======
			when {
				expression{
					env.BRANCH_NAME =='master-next'
				} 
			}
>>>>>>> dde9297... commiting on master next branch
			
			steps {
				echo 'testing the application...'
			 }
		 }
		 
		stage("deploy") {
<<<<<<< HEAD
=======
			when {
				expression{
					env.BRANCH_NAME =='master' || env.BRANCH_NAME == 'master-next'
				} 
			}
>>>>>>> dde9297... commiting on master next branch
			
			steps {
				echo 'deploying the application...'
			 }
		 }
	 }

}
