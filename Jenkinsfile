pipeline {
    agent any
    tools {
        maven 'Maven 3.9.6'  // Use the name you specified
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}
