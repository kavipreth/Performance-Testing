pipeline {

	agent any
  
  stages {
   
    stage('Execute Jmeter') {

	    
	    steps {
              bat("dir")
              bat("jmeter -n -t IMPS_Login_LogOut (1) -l 1.jtl")
      	}
      	
    }
  }
}
