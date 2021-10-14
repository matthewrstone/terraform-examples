# How this worked

1. Created an S3 bucket in AWS portal with no public access and server side encryption enabled.
2. Ran `terraform init` and supplied the S3 bucket name, region and key (for example: statefiles/thing.tf)
3. Ran terraform apply, supplied a name and region.
