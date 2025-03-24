pipeline {
  agent any
  stages {
    stage('') {
      steps {
        script {
          pipeline {
            agent any
            stages {
              stage('Test') {
                steps {
                  sh 'ansible --version'
                }
              }
            }
          }
        }

      }
    }

  }
}