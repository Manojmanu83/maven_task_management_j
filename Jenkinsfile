pipeline {
  agent any
  // agent {
  //   label 'java_slave_node'
  // }
  stages {
    stage('print info of server') {
      steps {
        sh"""
        echo ${env.JOB_NAME}
        echo ${env.BUILD_ID}
        echo $JOB_NAME
        echo $HOSTNAME
        pwd 
        uptime
        whoami
        """
      }
    }
  }
}
