
pipeline {
  agent{
    docker {image 'python-dev:latest'}
  }
  stages {
    stage('version') {
      steps {
        sh 'python3 --version'
      }
    }
    stage('main') {
      steps {
        sh 'python3 main.py'
      }
    }
    stage('math'){
      steps{
        sh 'python3 math.py'
      }
    }
  }
}
