pipeline {
   agent any

   stages {
      stage('build') {
         steps {
            sh "build"
         }
      }
       stages {
      stage('test') {
         steps {
            sh "test"
         }
      }
       stages {
      stage('deploy') {
         steps {
            sh "deploy"
         }
      }
      
   }
}
