
pipeline {
	agent any
	tools {
		maven "maven"
	}
	stages {
		stage('Maven install') {
			steps {
				sh 'mvn clean install'
			}
	
		}
		stage('Dockerbuild') {
			steps {
				sh 'docker build -t springpetclinc:latest .'
			}
		}
	}
}
