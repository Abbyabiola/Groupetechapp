pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
              echo "cloning the code"
              
           }
       }
      stage('deploy Code') {
        steps{
            sh 'ls -l'
       
                }
            }
            stage('Unitest') {
                steps {
                    sh 'systemctl status jenkins'
                }
            }
        parallel{
            stage('test') {
                steps {
                    sh 'lsblk'
                }
            }
            stage('deploy') {
                steps {
                    sh 'whoami'
                }
            }
        }
      
   }
}
   

