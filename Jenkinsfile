pipeline {
  agent any
  stages {
    stage('Git clone') {
      steps {
        sh 'cd /jenkins && rm -Rf Mozo-NG'
        sh 'cd /jenkins && git clone git@github.com:VinaTech/Mozo-NG.git && ll'
      }
    }
  }
}