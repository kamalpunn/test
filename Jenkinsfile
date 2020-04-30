pipeline {
  agent none
  stages {
    stage('build') {
      parallel {
        stage('build') {
          steps {
            sleep 1
          }
        }

        stage('') {
          steps {
            ws(dir: 'kp')
          }
        }

      }
    }

  }
}