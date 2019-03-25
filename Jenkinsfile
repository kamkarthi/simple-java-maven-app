#!groovy
pipeline {
  agent none
    stages {
      stage('Build') {
        agent { label 'ecs' }

        steps {
          sh 'echo hello'
        }
      }
    }
}
