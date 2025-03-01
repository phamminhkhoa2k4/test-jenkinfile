pipeline {
    agent any

    stages {
        stage('Clone') {
            steps {
                git branch: 'main', url: 'https://github.com/phamminhkhoa2k4/test-jenkinfile.git'
            }
        }

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
// pipeline {
//     agent any
//     stages {
//         stage('Build') {
//             steps {
//                 sh 'docker build -t myapp .'
//             }
//         }
//         stage('Run') {
//             steps {
//                 sh 'docker run -d -p 8080:8080 myapp'
//             }
//         }
//     }
// }
