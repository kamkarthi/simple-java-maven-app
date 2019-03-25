pipeline {
  agent none
    stages {
      stage('Build') {
        agent { label 'ecs' }

        steps {
          sh 'echo Build Stage'
        }
      }
      stage('Test') {
        agent { label 'ecs' }

        steps {
          sh 'echo TEST Stage'
        }
      }
    }
}
