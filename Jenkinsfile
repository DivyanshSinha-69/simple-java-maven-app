pipeline {
    agent any
    tools {
        maven 'M3'  // Use the name you specified
    }
    stages {
        stage('Build') {
            steps {
                bat 'mvn -B -DskipTests clean package'
            }
        }
    }
}
