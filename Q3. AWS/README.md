
## 1. How do you backup an instance:
Ans:<br/> 
AWS have backup service for the backup of any machine , volume or rds instances 
also we can create an AMI of a EBS backed EC2 by console or cli 


## How do you secure s3 buckets?
Ans: <br/>

1. By disabling public access
2. Enabling Encryption on objects 
3. providing both bucket policy , IAM policy for bucket and objects
4. for temporary use to use presigned url for  objects

## Why do we subnets:
Ans: <br/>

Device Reachability: <br/>
subnetting narrows down the IP address to usage within a range of devices.

security: <br/>
provides security of network within network 

High Availability: <br/>
subnets enable group of ec2 to work in close to each other in a given AZ
also enables the High avaialability of a given application if you create a
subnet for each AZ and deploy your application in each subnet spanning entire region



