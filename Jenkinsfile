node{
	stage('Git-Checkout'){
	
		echo "Checking out from Git Repo";
		//git 'https://github.com/Niha-21/tycompwebapp.git'
		scm checkout
	}
        stage('Mvn Package'){
		def mvnHome = tool name: 'Maven', type: 'maven'
		def mvnCMD = "${mvnHome}/bin/mvn"
		sh "${mvnCMD} clean package"	
	}

        
}
