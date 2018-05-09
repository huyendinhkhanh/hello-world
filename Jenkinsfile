pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        chmod +x hello-world.sh
        ./hello-world.sh
      }
    }
  }
}
