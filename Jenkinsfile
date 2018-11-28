#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

       stage('BuildArtifact'){
          

  
   withEnv(["PATH=${M2_HOME}/bin:${PATH}"]) {
      sh 'mvn -B verify'
   }
}
       }
	   
      
       
}

