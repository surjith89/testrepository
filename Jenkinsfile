env.ARTIFACT_LOCATION = "/output/${env.BUILD_TAG}"
env.LOCAL_CONTAINER = "${env.BUILD_TAG}"
env.REGION = 'us-east-1'
env.PROJECT_PATH = 'test-utils/'
env.ACTION = params.action
env.ENVIRONMENT = params.environment
def mvn_version = 'M3'

node {
    stage ('Checkout') {
        checkout scm
            }
 }