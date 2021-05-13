pipeline {
  agent {
   label 'docker-maven-slave'
  }

  stages {
   stage('Run Maven Build') {
    steps {
      sh 'mvn package'
     }
   }
  }
}
