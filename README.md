# Integration with AWS Kinesis, Lambda and mount EFS in the Lambda function Using Cloud formation .

Created Kinesis Event Bus and data stream for data streaming and then created two lambda function one is for Kinesis producer and one is for consumer.

producer lambda send the data to kinesis data stream and then kinesis will send back the data to consumer lambda for further processing .

created VPC, Subnets for EFS and then created EFS , Access point under the vpc and subnets , lastly mounted the EFS in to the producer lambda function.
