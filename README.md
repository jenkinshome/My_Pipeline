# My_Pipeline
pipeline {
   agent any
       stages {
         stage ('HELLO') {
            steps {
               echo "HELLO WORLD "
               }
             }
           }
        }
