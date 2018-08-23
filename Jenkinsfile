#!/usr/bin/env groovy
pipeline {
    agent { label 'dockerserver' }
    stages {
        stage('build plugin') {    
@Library('pipeline-library')_
/* `buildPlugin` step provided by: https://github.com/jenkins-infra/pipeline-library */
buildPlugin()
        }
    }
}
