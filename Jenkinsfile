pipeline {
  agent {
    label 'java_slave_node'
  }
  stages {
    stage('print info of server') {
      steps {
        sh"""
        echo ${env.JOB_NAME}
        echo ${env.BUILD_ID}
        hostname
        pwd 
        uptime
        whoami
        """
      }
    }
  }
}
