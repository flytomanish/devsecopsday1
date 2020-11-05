pipeline {

agent any

tools {
        maven 'maven'

   }
   
stages {

        stage('checking maven installation') {
   
             steps {
                    sh 'mvn -v'
             }
        }
        stage('Building java Project') {
                
                steps {
                        sh 'mvn clean package'
                }
                
        }
        

  }



}
