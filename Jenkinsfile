#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('BuildArtifact'){
          
	 sh 'M2_HOME=/opt/apache-maven-3.6.0'
            sh 'PATH=${M2_HOME}/bin:${PATH}'
          sh 'mvn install'
       }
	   
      
       
}
