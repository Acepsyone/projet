pipeline {
    agent any
    tools {
        jdk "jdk17-0-5"
    }
    stages {
        stage('Build') {
            steps {
               git 'https://github.com/Acepsyone/projet.git'
                dir ("projet") {
                sh "chmod +x ./gradlew"
                sh "./gradlew build"
                }
            }
        }
    }
}
