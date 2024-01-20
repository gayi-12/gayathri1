Resources:
  S3Bucket:
    Type: 'AWS::S3::Bucket'
    Properties: 
       BucketName: "Demo.aws.gayi.example.com"
       VersioningConfiguration:
        Status: Enabled
