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
	}
}
