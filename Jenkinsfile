pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
               sh """
               echo "Building Artifact. 54321abcde"
               """
           }
       }
      stage('Deploy Code') {
          steps {
               sh """
               echo "Deploying Code, abcde12345"
               """
          }
      }
   }
}
