pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'i am ready to n ....'
            }
        }
        stage('Working with') {  // Changed the name to 'Working with'
            steps {
              //  sh  'mkdir working'
                sh 'ls -la'
                sh 'touch sai'
                sh 'rm -rf sai'
            }
        }
    }
}
