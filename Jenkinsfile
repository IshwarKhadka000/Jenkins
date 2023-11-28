pipeline {
    agent any
    stage('build') {
  steps {
    sh 'docker pull maven:3.9.5-eclipse-temurin-17-alpine'
    sh 'docker run -it maven:3.9.5-eclipse-temurin-17-alpine mvn --version'
  }
}
}