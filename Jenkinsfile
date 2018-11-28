#!groovy

node {
	   
	stage('SCM Checkout'){

          checkout scm
       }
	stage('MVN Package') {
		def mvnHome = tool name: 'maven', type: 'maven'
		def mvnCMD="${mvnHome}/bin/mvn"
		sh "${mvnCMD} clean package"
	  }
    }

      
