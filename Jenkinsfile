	node('') 
	{
		withEnv([
         "PATH+MAVEN=${tool 'Maven 3.5'}/bin",
         "JAVA_HOME=${tool 'JDK 8u144'}"])
         {
			stage("CheckoutAndBuild") 
			{	 
                                echo "Checking out Code for master"
				cleanWs deleteDirs: true
				checkout ([$class: 'GitSCM', branches: [[name: "master"]],userRemoteConfigs: [[ url: 'https://github.com/sumanthskies/DevOpsClassCodes.git']]])
                                echo "Checking out finished"
                        }
         }

    }
