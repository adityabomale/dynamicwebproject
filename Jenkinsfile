pipeline {
agent any
	tools {
		maven "M3"
		}
	stages {
		stage ('checkout') {
		steps {
			git branch: 'main', url: 'https://github.com/adityabomale/dynamicwebproject.git'
		}}
		stage ('maven build') {
		steps {
			sh 'mvn clean install'
			}
			}
			}
			}
		
