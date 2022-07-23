#!/usr/bin/groovy

@Library('jenkins_lib') _
pipeline {                     
    agent any
    environment {
        New_version = "1.2"
        code_owner = "faizan"
    }
    parameters {
        choice choices: ['karan', 'faizan'], description: 'Testing', name: 'Name'
    }
    stages {
        stage('Hello') {
            steps {
                echo "version name is ${New_version}"
                echo "code owner is ${code_owner}"
                echo "${Name}"
            }
        }
    }
}

