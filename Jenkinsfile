pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ehco "Hello World"'
		sh '''
			ehco "Multiline shell steps working too"
			ls -lah
		'''
      }
    }
  }
}