# SpringBootApp

Tools Required:

        Install Maven and  define the M2_HOME environment variable name as 'Maven_3.2.5' in the jenkins tools section
		
        Install JDK8 and define the JAVA_HOME environment variable name as 'JDK8_131' in the jenkins tools section
		
		Or Update the environment variables in the Jenkinsfile. 

Parameters Required for Jenkins Pipeline Job :

	<SONAR_HOST> --> SONAR Host Name
	
	<SONAR_PORT> --> SONAR Host Port 
	 
	<SONAR_USER_TOKEN_ID> --> SONAR User Token ID ( required for sonar login, generated through Sonar UI and no need to pass SONARQUBE username and password)
	
	<DOCKER_PRIVATE_REGISTRY_HOST> --> Nexus Private Registry Host Or IP
	
	<DOCKER_PRIVATE_REGISTRY_PORT> --> Nexus Private Registry Port ( Docker Repo HTTP or HTTPS Port )
