
@Library('pipeline-library')_


pipeline {
    agent any
     
    stages {
    stage ('Example') {
        steps {
            sh 'sleep 200'
             script { 
                 buildPlugin()
             }
        }
    }
}
}
