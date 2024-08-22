// node {
// 	stage('Build') {
// 		echo "Build"
// 	}
// 	stage('Test') {
// 		echo "Test"
// 	}
// 	stage('IntegrationTest') {
// 		echo "Test"
// 	}
// }

pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "build"
            }
        }
        stage("Test"){
            steps{
                echo "Test"
            }
        }
        stage("IntegrationTest"){
            steps{
                echo "IntegrationTest"
            }
        }
    }
}