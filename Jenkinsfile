pipeline {
  agent any
  stages {
    stage('git') {
      steps {
        git(url: 'https://github.com/Sivada12/petclinic.git', branch: 'CI/CFD', credentialsId: 'a79ed2e2-b2da-4422-9f8d-5c2febe66268')
      }
    }

  }
}