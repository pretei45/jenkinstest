pipeline{
	agent any
	stages{
		stage('1-Memory'){
			steps{
				sh 'du -h'
				sh 'free -g'
			}
		}
		stage('2-Test'){
			steps{
				echo "stage 2 running"
			}
		}
	}
}
