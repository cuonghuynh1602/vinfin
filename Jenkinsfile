pipeline {
  agent any
  stages {
    stage('Git clone') {
      steps {
        sh 'cd /jenkins && git clone git@github.com:VinaTech/Mozo-NG.git && ll'
      }
    }
  }
}