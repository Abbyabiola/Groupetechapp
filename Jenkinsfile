pipeline {
   agent any
   stages {
       stage('Build Code') {
           steps {
              echo "cloning the code"
              echo "building the code"
           }
       }
      stage('Deploy Code') {
        steps{
            sh 'ls -l'
       
                }
            }
            stage('Unitest') {
                steps {
                    sh 'systemctl status jenkins'
                }
            }
        parallel {
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
   }

