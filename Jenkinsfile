pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
           echo "build success"    
      }
    }

    stage('Test') {
      steps {
          echo "mvn test starts"
       
      }
    }

     stage('Deploy Development') {
      steps {
            bat "mvn clean package deploy -DmuleVersion=4.4.0 -Dusername=deepthivelakaturi2 -Dpassword=5@eggs@WEAR@8 -DapplicationName=flightsapp-ws-omvk958 -Denvironment=Sandbox -Dworkers=1 -DworkerType=Micro -DmuleDeploy"
            echo "deploy success"      
}}}}
