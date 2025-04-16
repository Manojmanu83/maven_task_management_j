pipeline {
  agent any
  stages {
    stage('print info of server') {
      steps {
        sh"""
        echo $JOB_NAME
        echo $BUILD_ID
        ehco $HOSTNAME
        pwd 
        uptime
        whoami
        """
      }
    }
  }
}
