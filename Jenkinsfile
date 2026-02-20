// pipeline {
//     agent {
//         node {
//             label 'jenkins-node-1'
//         }
//     }
//     stage('Build') {
//         steps {
//             echo 'Building...'
    
//         }
//     }
//     stage('Test') {
//         steps {
//             echo 'Testing...'
            
//         }
//     }
//     stage('Deploy') {
//         steps {
//             echo 'Deploying...'
            
//         }
//     }
// }

pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing...'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Deploying...'
            }
        }
    }
}