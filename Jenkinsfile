pipeline {
agent any
stages{
   stage('Build'){
      steps{
         sh '/home/elkhiri/maven/apache-maven-3.6.3/bin/mvn clean install'
      }
   }
   stage('Test'){
      steps{
         sh '/home/elkhiri/maven/apache-maven-3.6.3/bin/mvn test'
      }
   }
}
}
