pipeline {
  agent any
  stages {
    stage('clone repo') {
      steps {
        sh 'git clone https://github.com/sivaamb/sivaapp.git'
      }
    }

    stage('build clean') {
      steps {
        sh '/opt/maven/bin/mvn test -f sivaapp'
      }
    }

  }
}