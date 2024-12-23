pipeline {
    agent {
        docker{
            image 'maven'
        }
    } 

    
    stages {
        stage('Hello') {
            steps {

                // Run Maven on a Unix agent.
                sh "mvn -version"

                // To run Maven on a Windows agent, use
                // bat "mvn -Dmaven.test.failure.ignore=true clean package"
            }
        }
    }
}
