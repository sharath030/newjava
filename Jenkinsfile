pipeline {
  agent any
  stages {
    stage('BUILD') {
      steps {
            sh '''
               #!/bin/bash
                   echo "this is the first build stage in Jenkinsfile" 
                   sleep 10
                    '''
      }
    }
    stage('TEST1') {
      steps {
              sh 'echo "this is the first test stage in Jenkinsfile"'
                    sleep 10
      }
    }
    stage('TEST2') {
      steps {
             sh 'echo "this is the second test stage in Jenkinsfile"'
                        sleep 10
      }
    }
    stage('DEPLOY') {
      steps {
                sh 'echo "this the final deploy stage in Jenkinsfile"'
                             sleep 10
      }
    }
  }
}
