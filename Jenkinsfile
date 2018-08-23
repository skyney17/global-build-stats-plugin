
@Library('pipeline-library')_


pipeline {
    // agent { label 'linux' }
     
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
