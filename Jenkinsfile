pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                sh 'mvn -DskipTests clean packages'
            }
	      }
        stage("Test"){
            steps{
                sh 'mvn test'
            }
        }
    
    }
}
