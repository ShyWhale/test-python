
pipeline {
  agent{
    docker {image 'continuumio/conda-ci-linux-64-python3.8:latest'}
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
