pipeline {
	agent any
    stages {
        stage('build') {
			agent {
                label "stage_api"
            }
            when {
                beforeAgent true
                branch 'master'
            }
            steps {
                echo 'BUILDING...'
            }
		}
	}
}