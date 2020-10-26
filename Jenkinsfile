pipeline{
  agent any
  tools{
  maven 'Maven 3.6.3'
  jdk 'jdk 11.0.8'
  }
	  stages{
			  stage('Initialize'){
					  steps{
					  bat echo "mvn = ${MAVEN_HOME}"
					  bat echo "jdk = ${JAVA_HOME}"
					  }
			  }
	  }
}