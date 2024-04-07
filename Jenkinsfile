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
                sh './tools/ci/test_controller.sh core'
                java -version
                mvn -version
            }
        }
    }
}
