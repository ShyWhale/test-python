
pipeline {
  agent {
    docker {image 'devopsjourney1/myjenkinsagents:python'}
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
