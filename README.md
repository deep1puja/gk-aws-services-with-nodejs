# AWS services with NodeJS
## REST API
### To Get all products from Redshift
GET http://localhost:3000/redshift/getproduct

### Insert producut(s) into Redshift from S3 JSON file
GET http://localhost:3000/redshift/set-product-from-s3-json?keyName=products.json

### Read Json file from S3
GET http://localhost:3000/files?keyName=products.json

### List all  files from S3
GET http://localhost:3000/files/list

### upload new file to S3
POST http://localhost:3000/files
param = {file:objectfile}
