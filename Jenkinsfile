pipeline {
  agent {
   label 'docker-maven-slave'
  }

  stages {
   stage {
    steps {
      sh 'mvn package'
     }
   }
  }
}
