pipeline {
    agent any
    stages {
        stage('build'){
            steps {
                echo "Some weird text"
                sh "./gradlew build --no-daemon"
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
