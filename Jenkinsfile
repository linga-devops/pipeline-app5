pipeline {
    agent any 
    stages {
          stage('----Build----') 
             {
               steps{
              sh "rm -rf pipeline-app5"
              echo "This is Build stage"
              echo "===================================="
               }
             }
             stage('----Test----') 
             {
             steps{
              echo "This is Test stage"
              echo "===================================="
             }
             }
              stage('----QA----') 
             {
             steps{
              echo "This is QA stage"
              echo "===================================="
             }
             }
              stage('----Deploy----') 
             {
             steps{
              echo "This is Deploy stage"
              echo "===================================="
             }
             }
             
              stage('----Monitor----') 
             {
             steps{
              echo "This is Monitor stage"
              echo "===================================="
             }
             }
             
            }
       }
