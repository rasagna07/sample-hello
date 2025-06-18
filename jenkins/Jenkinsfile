pipeline {
    agent any
    stages {
        stage('Build 07') { 
            steps {
                sh 'mvn -B -DskipTests clean package' 
            }
        }
    }
}
