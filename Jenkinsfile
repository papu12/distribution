pipeline {
  agent any
  stages {
    stage('step1') {
      steps {
        sleep 30
        archiveArtifacts 'sss'
        node(label: 'ssss')
        bat(script: 'sss.sh', encoding: 'sss', returnStatus: true, returnStdout: true)
      }
    }
  }
}