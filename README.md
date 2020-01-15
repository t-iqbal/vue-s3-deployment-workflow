# vue-s3-deployment-workflow
<<<<<<< HEAD

## This is an example Github's actions that lets you build Vue project and upload it's deployment artifacts to AWS S3

### Create AWS Access Key Id and S3 Bucket
Create an AWS access key - See [Create Reference](https://aws.amazon.com/premiumsupport/knowledge-center/create-access-key/)
and Create AWS S3 Bucket - See [Create S3 Bucket Reference](https://docs.aws.amazon.com/AmazonS3/latest/gsg/CreatingABucket.html)

### Project setup
```
Go to Actions tab of your Vue repo in in Github and click on button "Set up a workflow on yourself".
```

### Setup AWS Crdenentails and S3 Bucket name
```
Go to Settings tab of your repo then Secrets button and add  AWS_ACCESS_KEY_ID, AWS_SECRET_ACCESS_KEY and S3_BUCKET_NAME.
```

### Trigger workflow
```
Commit any changes to repo triggers workflow and build and deploy it's artifacts to AWS S3.
```

=======
An example workflow that lets build Vue project and upload it to AWS S3
>>>>>>> 796ab357f31ddafdaa5f52a7771792d4b51eac0c
