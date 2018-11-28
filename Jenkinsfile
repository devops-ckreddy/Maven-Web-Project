#!groovy

node {
	   
	stage('SCM Checkout'){

          checkout scm
       }
	stage('MVN Package') {
		def mvnHome = tool name: 'M3', type: 'maven'
		def mvnCMD="${mvnHome}/bin/mvn"
		sh "${mpvnCMD} clean package "
	  }
    }

      
