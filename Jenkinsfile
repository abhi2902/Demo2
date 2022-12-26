pipeline {
    agent any


    stages {
        stage('Hello') {
            steps {
                
                sh 'echo Hello'

            }

        }
        stage('Prepration') {
            steps {
                
                git 'https://github.com/pythonprofilers/memory_profiler.git'

            }

        }
        stage('Build') {
            steps {
                
                sh 'pip install .'

            }

        }
      stage('GoodBye...') {
            steps {
                
                sh 'echo GoodBye...'

            }

        }
    }
}
