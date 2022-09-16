pipeline {
agent any
	tools {
		maven "MAVEN_HOME"
		jdk "JAVA_HOME"
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
		
