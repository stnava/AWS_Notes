# AWS_Notes
Notes on usage of amazon web services for distributed computing

See [this link first](https://aws.amazon.com/blogs/opensource/aws-parallelcluster/)

See [hpc on amazon](https://aws.amazon.com/hpc/)

## Create s3 bucket

Store data in a bucket.  You should create a different bucket for each project which allows one to break down storage costs by project.

https://docs.aws.amazon.com/AmazonS3/latest/gsg/CreatingABucket.html

you can also use the aws command line client.

```
aws s3 mb s3://example-bucket
```

## Copy data to S3 bucket

```
aws s3 cp help
```

## Install software

[https://docs.aws.amazon.com/parallelcluster/latest/ug/pre_post_install.html](https://docs.aws.amazon.com/parallelcluster/latest/ug/pre_post_install.html)

## Submit jobs

https://aws.amazon.com/blogs/opensource/aws-parallelcluster/

## Re-submit jobs

still an open question

https://github.com/aws/aws-parallelcluster/issues/1077

