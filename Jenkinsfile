	node('') 
	{
		withEnv([
         "PATH+MAVEN=${tool 'Maven 3.5'}/bin",
         "JAVA_HOME=${tool 'JDK 8u144'}"])
         {
			stage("CheckoutAndBuild") 
			{	 
               git 'https://github.com/sumanthskies/DevOpsClassCodes.git' 
            }
         }

    }
