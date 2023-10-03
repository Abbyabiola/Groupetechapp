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
      
      stage('parallel') {
        parallel{
            stage('build') {
                steps {
                    echo "We are the group 2 the  upcoming devops engineers"
                }
            }
            stage('Unitest') {
                steps {
                    sh 'systemctl status jenkins'
                }
            }
        stage('parallel') {
        parallel {
            stage('Test') {
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
}
}