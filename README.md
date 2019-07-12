# serverless-s3-static

> Example project AWS S3 static web hosting with serverless

## Usage

Make sure serverless can access your aws.

Follow [Serverless credentials guide](https://serverless.com/framework/docs/providers/aws/guide/credentials/)

You can modify region, bucketName in `serverless.yml`.

**Note**: Make sure `bucketName` in `serverless.yml` unique.

``` bash
# deploy
$ npm run static-deploy
```
