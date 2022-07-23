@Library('jenkins_lib') _
pipeline {                     
    agent any
    environment {
        New_version = "1.2"
        code_owner = "faizan"
    }
    stages {
        stage('Hello') {
            steps {
                echo "version name is ${New_version}"
                echo "code owner is ${code_owner}"
                test('faizan')
            }
        }
    }
}

