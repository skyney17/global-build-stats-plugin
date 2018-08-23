
@Library('pipeline-library')_

pipeline {
     agent { label 'dockerserver' }
    stages {
    stage ('Example') {
        steps {
             script { 
                 buildPlugin()
             }
        }
    }
}
}
