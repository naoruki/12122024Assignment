# 12122024Assignment

aws elasticbeanstalk create-application-version \
    --application-name cornelia \
    --version-label v1.0.1 \
    --source-bundle S3Bucket="my-bucket",S3Key="Corneliaapp.zip" 