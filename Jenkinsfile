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
      stage('Test Code') {
        parallel {
            stage('build') {
                steps {
                    echo "We are the group 2 the  upcoming devops engineers"
                }
            }
            stage('unitest') {
                steps {
                    sh 'systemctl status jenkins'
                }
            }
        stage ('security test') {
            steps {
                sh 'whoami'
            }
        }
        }
        parallel {
            stage('test') {
                steps {
                    sh 'lsblk'
                }
            }
            stage('Deploy') {
                steps {
                    sh 'whoami'
                }
            }
        }
      
   }
}
   }
