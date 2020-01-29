## AWS Services

See LinkedIn course [Learning AWS for developers](https://www.linkedin.com/learning/learning-amazon-web-services-aws-for-developers)
### DynamoDB

- fast and flexible NoSQL database service
- suitable for document and key-value store models

##### Benefits
- always stored on SSD (you get great disk throughput)
- high availability built-in
- fast and flexible
- suited for read heavy applications

##### Read Consistency
- eventually consistent reads (default)
- strongly consistent reads

Due to data replication to the three geographically distinct data centers on which DynamoDB is being stored 
and it isn't instant, it takes couple of seconds or less, but it takes some time.
So you can choose your read consistency depending on whether you want users to be guaranteed to have the correct data or 
whether on occasions when they run a query they might not get the latest up-to-date version.

"Dirty read" - you request a read but do not receive the up-to-date version.


##### Useful links

- [AWS DynamoDB Tutorial](https://www.youtube.com/watch?v=2mVR_Qgx_RU)


### Lambda
- no servers to maintain - serverless
- supports code C#, Java, Python, Node.js, Go 
- could be triggered as result of events happening from many AWS services, like S3, DynamoDB, etc 

##### Useful links
- [Lambda](https://www.linkedin.com/learning/learning-amazon-web-services-aws-for-developers/lambda)
- [AWS Lambda Tutorial](https://www.youtube.com/watch?v=XZggsCITQdY)