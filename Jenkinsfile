pipeline {
 agent any
  stages {
      stage('Pull') {
         steps {
             git 'https://github.com/Devops-trainer1987/ctsdecproj2.git'
         }
      }
      stage('Package') {
         steps {
            bat 'mvn package'
         }
      }
      stage('Execute') {
         steps {
            bat 'java -jar "C:/ProgramData/Jenkins/.jenkins/workspace/job55/target/cts1-1.0-SNAPSHOT.jar"'
         }
      }
   }
}
