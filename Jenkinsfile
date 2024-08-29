// pipeline {
//     agent any

//     environment {
//         DOCKER_IMAGE = "priyanaresh/dockjenk"
//     }

//     stages {
//         stage('Clone Repository') {
//             steps {
//                 git branch: 'main', url: 'https://github.com/PriyaNaresh7022/YourRepo.dockjenkin.git'
//             }
//         }

//         stage('Build Docker Image') {
//             steps {
//                 script {
//                     docker.build("${DOCKER_IMAGE}:${env.BUILD_ID}", '.')
//                 }
//             }
//         }

//         stage('Run Docker Container') {
//             steps {
//                 script {
//                     docker.image("${DOCKER_IMAGE}:${env.BUILD_ID}").run('-p 8080:80')
//                 }
//             }
//         }
//     }

//     post {
//         always {
//             cleanWs()
//         }
//     }
// }
