pipeline {
  agent {
    node {
      label '123'
    }

  }
  stages {
    stage('init') {
      steps {
        sleep 11
      }
    }

    stage('start') {
      steps {
        input(message: 'qingshuru', id: 'dw', ok: 'success', submitter: 'dwe', submitterParameter: 'few')
        warnError(message: '313') {
          echo '45646'
        }

      }
    }

  }
}