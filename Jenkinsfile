pipeline {
   agent any
   
   stages {
      stage('compile') {
         steps {
            sh 'cd /var/lib/jenkins/workspace/sakthipipeline'
            sh 'javac add.java'
            sh 'java add'
         }
      }
      
   }
}
