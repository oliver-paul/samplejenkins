pipeline {

    agent { label 'master' }

    environment {
        bucket_name = 'survey-sparrow-marketplace-developer-source-code'
        api_gateway_endpoint = 'https://iut8m37lrk.execute-api.us-east-1.amazonaws.com/testing/'
    }

    stages {
        stage('Upload source code to S3') {
            steps {
                //
                echo "Inside Upload source code to S3 ${params.Application}"
                sh """
                pwd
                ls -la
                """
                echo "${params.filePath}"
            }
        }
        stage('Creating Lambda') {
            steps {
                //
                echo "Inside Creating Lambda"
            }
        }
        stage('Uploading S3 code to Lambda') {
            steps {
                //
                echo "Inside Uploading S3 code to Lambda'"
            }
        }
        stage('API gateway path creation') {
            steps {
                //
                echo "Inside API gateway path creation"
            }
        }
    }
}
