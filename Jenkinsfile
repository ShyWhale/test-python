
// pipeline {
//   agent{
//     docker {image 'node:16.13.1-alpine'}
//   }
//   stages {
//     stage('version') {
//       steps {
//         sh 'python3 --version'
//       }
//     }
//     stage('main') {
//       steps {
//         sh 'python3 main.py'
//       }
//     }
//     stage('math'){
//       steps{
//         sh 'python3 math.py'
//       }
//     }
//   }
// }

pipeline {
    agent {
        docker { image 'node:16.13.1-alpine' }
    }
    stages {
        stage('Test') {
            steps {
                sh 'node --version'
            }
        }
    }
}
