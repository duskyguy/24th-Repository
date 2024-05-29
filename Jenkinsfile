pipeline{
    agent any

    stages{
        stage('build'){
            steps
            {
                
                bat 'C:/Users/bharg/Downloads/Maven/apache-maven-3.9.6/bin/mvn compile'

                                bat 'C:/Users/bharg/Downloads/Maven/apache-maven-3.9.6/bin/mvn clean'

                
                git 'https://github.com/davidB/scala-archetype-simple.git'
                
            }
        }
    }
}
