pipeline {
  agent any
  stages {
     stage('clone') {
        steps {
          git 'https://github.com/Pooja5129/project_jenkins-123.git'
        }
     }
   stage('Build') {
       steps {
         sh 'echo "building project ..."'
       } 
   }
   stage('Test') {
      steps {
        sh 'echo "Running test..."'
      }
   }
  }
}
