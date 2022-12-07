pipeline {

    agent { label 'master' }

    stages {
        stage('Upload source code to S3') {
            steps {
                //
                sh "unzip ${file1}"
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
