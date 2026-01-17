pipeline {
	agent any
	stages {
		stage('Build') {
			steps {
				sh 'mvn_3_9_12 -B -DskipTests clean package'
			}
		}
	}
}