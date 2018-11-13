#!groovy

node  {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('BuildArtifact'){
          // build step
          
         def mvn_version = 'maven'
         withEnv( ["PATH+MAVEN=${tool mvn_version}/bin"] ) {
          sh "mvn clean package"
}
       }
	   
      /*stage('Sonar') {
                    //add stage sonar
	      	 def mvn_version = 'M3'
               withEnv( ["PATH+MAVEN=${tool mvn_version}/bin"] ) {
              sh "mvn sonar:sonar"
                }*/
      }
       
}
