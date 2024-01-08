pipeline {
    agent any
     stages{
      stage('clean'){
       steps {
         sh 'mvn clean'
       }
    }
    stage('compile'){
       steps {
         sh 'mvn compile'
       }
    }
    stage('clean'){
       steps {
         sh 'mvn clean'
       }
    }
    stage('install'){
       steps {
         sh 'mvn install'
            'mvn package'
       }
    }
    
    }

}
