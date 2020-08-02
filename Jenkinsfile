	node('android') 
	{
		withEnv([
         "PATH+MAVEN=${tool 'Maven 3.5'}/bin",
         "JAVA_HOME=${tool 'JDK 8u144'}"])
     https://github.com/sumanthskies/DevOpsClassCodes.git  
         {
			stage("CheckoutAndBuild"+appName) 
			{	 
                git 'https://github.com/sumanthskies/DevOpsClassCodes.git'
            }
         }

    }
