pipeline {
  agent none
    stages {
      stage('Build') {
        agent { label 'ecs' }

        steps {
          sh 'mvn -B -DskipTests clean package'
        }
      }
      stage('Test') {
        agent { label 'ecs' }

        steps {
          sh 'mvn test'
        }
      }
    }
}
