pipeline {
	agent any
	stages{
		stage('build'){
			steps{
				echo "testing"
			}
		}
	}
	post{
	always{
		echo "built"
	}
	success{
		echo "Yeess "
	}
	}
}
