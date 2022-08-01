# aws_cloudformation_reactapp_pipeline


## create a s3 bucket to uploda your code to

```
aws s3 mb s3://aws_cloudformation_reactapp_pipeline_01-08-2022
```

## zip your application code

```
zip -r application.zip public scripts src appspec.yml buildspec.yaml package.json package-lock.json
```
