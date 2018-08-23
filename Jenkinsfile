
@Library('pipeline-library')_

pipeline {
     agent { label 'linux' }
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
