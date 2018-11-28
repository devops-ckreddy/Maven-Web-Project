#!groovy

node {
	   
	stage('Checkout'){

          checkout scm
       }

     
    
    }
stages {
        stage(Maven') {
	      MAVEN_HOME = tool('M3')
           sh '${MAVEN_HOME}/bin/mvn -B verify'
        }
    }
}
}
       }
	   
      
       
}

