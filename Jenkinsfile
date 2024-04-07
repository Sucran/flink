pipeline {
    agent any
    stages {
        stage("build") {
            steps {
                echo "building"
            }
        }
        stage("test") {
            steps {
                sh 'java -version'
                sh 'mvn -version'
            }
        }
    }
}
