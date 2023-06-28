pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                git 'https://github.com/tedyvrb/task07.git'
                python main.py
            }
        }
    }
}
