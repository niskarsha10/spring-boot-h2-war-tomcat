pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact. 54321"
               """
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code, 12345"
               """
          }
      }
   }
}
