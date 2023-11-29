pipeline {
   agent any
   stages{
    stage('Git Checkout') {
     steps{
          git branch: 'main', credentialsId: 'github-cred', url: 'https://github.com/Divyayenugula/demo25.git'
         }
       }
     stage('Build Stage') {
      steps{
         sh 'mvn clean package'

    }

   }

 }


}


























     




























    






