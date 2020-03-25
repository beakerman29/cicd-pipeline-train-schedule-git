pipeline {
    agent {
        node('master')
    }
   stages {
      stage('Download Source CentosTest2') {
        agent { 
            node('CentosTest02')
        }
        steps {
            // Get some code from a GitHub repository
            git poll: false, url: 'https://github.com/beakerman29/cicd-pipeline-train-schedule-git.git'
        }
      }
      stage('Download Source Centos Test') {
          agent {
              node('Centos Test')
          }
          steps {
            // Get some code from a GitHub repository
            git poll: false, url: 'https://github.com/beakerman29/cicd-pipeline-train-schedule-git.git'
          }
      }
   }
}
