pipeline {
  agent any
  options {
  skipDefaultCheckout true
          }
  stages{     
     stage ("Code Checkout") {
      steps {
        checkout scm
      }
     }
     
     
     stage ("Hellow World"){
       steps {
         sh'''
             echo "Hellow World From The Master Branch"
           '''
       }
     }
  }
}
