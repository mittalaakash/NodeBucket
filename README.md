# NodeBucket

## Overview

- Implement a basic object storage service with API similar to S3
- Use Express for web framework
- MongoDB for metadata database
- Local filesystem for object storage

### API Endpoints

- `GET /buckets` - List buckets
- `GET /buckets/:bucketName/objects` - List objects in bucket
- `GET /buckets/:bucketName/objects/:objectKey` - Get object
- `PUT /buckets/:bucketName/objects/:objectKey` - Create/update object
- `DELETE /buckets/:bucketName/objects/:objectKey` - Delete object
