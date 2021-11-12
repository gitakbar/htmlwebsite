pipeline { 
    agent any 
    
    stages {
        stage('Uploading to S3') { 
            steps { 
                sh 'aws s3 cp . s3://mysite9000 --recursive --acl public-read' 
            }
        }
    }
}
