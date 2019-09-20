pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'ehco "Hello World"'
		sh '''
			echo "Multiline shell steps working too"
		'''
      }
    }
  }
}