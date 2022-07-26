pipeline {
    agent any
    
    stage('build'){
        steps {
            
            sh "./gradlew build --no-daemon"
            
        }
    }
}
