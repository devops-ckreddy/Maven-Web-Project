#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('BuildArtifact'){
          
	  sh '/opt/apache-maven-3.6.0'
          sh 'mvn install'
       }
	   
      
       
}
