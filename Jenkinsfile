pipeline {
    agent any
    stages {
            stage {
			parallel {
                stage('stage one') {
                    agent {
                        label "stageonebranch"
                    }
                    steps {
                        echo "Me in stage one"
                    }
                }
                stage('Stage two') {
                    agent {
                        label "stage two"
                    }
                    steps {
                        echo "Me in stage two"
                    }
                }
                stage('Stage three') {
                    agent {
                        label "Stage Three"
                    }
					steps
					{
					echo "me in third stage"
                }
            }
        }
    }
}

}
