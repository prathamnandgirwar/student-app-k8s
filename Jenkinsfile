      
      pipeline{
      agent any
      stages{
      stage ('pull'){
      steps {
       git branch : 'main', url: 'https://github.com/prathamnandgirwar/student-app-k8s.git'
      }
      }
      stage ('build'){
      steps {
      echo "building the code"
      }
      }
      stage ('test'){
      steps {
      echo "testing the code"
      }
      }
      stage ('deploy'){
      steps {
      echo "deploying the app"
      }
      } 
      
      }
      
      }
