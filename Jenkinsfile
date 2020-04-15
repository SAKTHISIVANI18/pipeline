pipeline {
   agent any
   {
   stages {
      stage('build') {
         steps {
            sh 'cp /var/lib/jenkins/workspace/sakthipipeline/target/home/dineshreddy99077/che/apache-tomcat-7.0.103/webapps'
         }
      }
       
      stage('test') {
         steps {
            sh "test"
         }
      }
       
      stage('deploy') {
         steps {
            sh "deploy"
         }
      }
      
   }
}
