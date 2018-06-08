pipeline {
	agent any
    stages {
        stage('build') {
			agent {
                label "stage_api"
            }
            when {
                branch 'master'
            }
            steps {
                echo 'BUILDING...'
            }
		}
	}
}