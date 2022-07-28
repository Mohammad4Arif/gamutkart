pipeline {
    agent any
    stages {
        stage('stage1') {
            steps {
                script{
		bat "mvn clean install"
		   echo "stage one completd"
                }
            }
        }
	 stage('stage2') {
            steps {
                script{
			bat "mvn clean install"
		   echo "stage 2 completed"
                }
            }
        }
    }
}


