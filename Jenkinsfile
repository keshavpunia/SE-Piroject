pipeline {
    agent any 

    tools {nodejs "node"}

    stage(
        stage('Build') {
            steps {
                bat 'npm install'
            }
        }
    )
}