pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        Process p = Runtime.getRuntime().exec(new String[]{"bash","-c","./hello-world.sh"});
      }
    }
  }
}
