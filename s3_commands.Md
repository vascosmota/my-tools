# S3 AWS CLI Commands

## Move files

Move all files from one directory (and bellow) to another

```
aws s3 mv s3://bcuket/folderB/ s3://bucket/folderA/ --exclude "*.parquet" --recursive
```

