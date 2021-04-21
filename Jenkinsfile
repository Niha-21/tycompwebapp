node{
	stage('Git-Checkout'){
	
		echo "Checking out from Git Repo";
		//git 'https://github.com/Niha-21/tycompwebapp.git'
		checkout scm
	}
        stage('Mvn Package'){
		bat "sample.bat"
	}

        
}
