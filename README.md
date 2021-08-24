# aws-solutions-architect
This repo is a guide to taking solutions architect associate cert in 2021. The main [overview of the exam](https://github.com/MattN-HB/aws-solutions-architect/blob/main/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf) and [AWS official site](https://aws.amazon.com/certification/certified-solutions-architect-associate/). 

## My Key Resources: 
* [acloudguru hands on course](https://acloudguru.com/course/aws-certified-solutions-architect-associate-saa-c02)
* These amazing [practice exams with explanations](https://www.udemy.com/course/aws-certified-solutions-architect-associate-amazon-practice-exams-saa-c02/)
* These amazing [study guides/cheat sheets](https://tutorialsdojo.com/aws-cheat-sheets/)

## Scoring
* 100 - 1000 with minimum 720
* scaled scoring model
* 15 unscored questions that do not affect your score
* Unanswered questions are scored as incorrect; there is no penalty for guessing
* Multiple-choice: Has one correct response and three incorrect responses (distractors).
* Multiple-response: Has two or more correct responses out of five or more options

## Domain Breakdown 
<details>
  <summary>Domain 1: Design Resilient Architectures 30%</summary>

1.1 Design a multi-tier architecture solution
* Determine a solution design based on access patterns.
* Determine a scaling strategy for components used in a design.
* Select an appropriate database based on requirements.
* Select an appropriate compute and storage service based on requirements.
  ![image](https://user-images.githubusercontent.com/44328319/130339173-4edaa5d0-ac67-463a-ac16-84ac8e6d3762.png)


1.2 Design highly available and/or fault-tolerant architectures
* Determine the amount of resources needed to provide a fault-tolerant architecture across
Availability Zones.
* Select a highly available configuration to mitigate single points of failure.
* Apply AWS services to improve the reliability of legacy applications when application changes
are not possible.
* Select an appropriate disaster recovery strategy to meet business requirements.
* Identify key performance indicators to ensure the high availability of the solution.
1.3 Design decoupling mechanisms using AWS services

* Determine which AWS services can be leveraged to achieve loose coupling of components.
* Determine when to leverage serverless technologies to enable decoupling.

1.4 Choose appropriate resilient storage
* Define a strategy to ensure the durability of data.
* Identify how data service consistency will affect the operation of the application.
* Select data services that will meet the access requirements of the application.
* Identify storage services that can be used with hybrid or non-cloud-native applications.
  ![image](https://user-images.githubusercontent.com/44328319/127782754-f30964b3-d76f-4d82-855f-aac0b188ad15.png)

</details>
<details>
  <summary>Domain 2: Define Performant Architectures 28%</summary>

2.1 Identify elastic and scalable compute solutions for a workload
* Select the appropriate instance(s) based on compute, storage, and networking requirements.
* Choose the appropriate architecture and services that scale to meet performance
requirements.
* Identify metrics to monitor the performance of the solution.

2.2 Select high-performing and scalable storage solutions for a workload
* Select a storage service and configuration that meets performance demands.
* Determine storage services that can scale to accommodate future needs.

2.3 Select high-performing networking solutions for a workload
* Select appropriate AWS connectivity options to meet performance demands.
* Select appropriate features to optimize connectivity to AWS public services.
* Determine an edge caching strategy to provide performance benefits.
* Select appropriate data transfer service for migration and/or ingestion.

2.4 Choose high-performing database solutions for a workload
* Select an appropriate database scaling strategy.
* Determine when database caching is required for performance improvement.
* Choose a suitable database service to meet performance needs.
</details>
<details>
  <summary>Domain 3: Specify Secure Applications and Architectures 24%</summary>

3.1 Design secure access to AWS resources

* Determine when to choose between users, groups, and roles.
* Interpret the net effect of a given access policy.
* Select appropriate techniques to secure a root account.
* Determine ways to secure credentials using features of AWS IAM.
* Determine the secure method for an application to access AWS APIs.
* Select appropriate services to create traceability for access to AWS resources.
  ![image](https://user-images.githubusercontent.com/44328319/130360611-4d6bedb6-9d8b-495d-845b-6dbe3f69eb06.png)


3.2 Design secure application tiers

* Given traffic control requirements, determine when and how to use [security groups](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-network-security.html#security-group-rules) and
network ACLs. **TIP:** "Security Group acts as a firewall, it will only control both inbound and outbound traffic at the instance level and not on the whole VPC."
  ![image](https://user-images.githubusercontent.com/44328319/130416440-a16490e8-2698-4da1-a67d-d77c8ee3f000.png)

* Determine a network segmentation strategy using public and private subnets.
* Select the appropriate routing mechanism to securely access AWS service endpoints or
internet-based resources from Amazon VPC.
* Select appropriate AWS services to protect applications from external threats.

3.3 Select appropriate data security options

* Determine the policies that need to be applied to objects based on access patterns.
* Select appropriate encryption options for data at rest and in transit for
</details>
<details>
  <summary>Domain 4: Design Cost-Optimized Architectures 18%</summary>

4.1 Identify cost-effective storage solutions
* Determine the most cost-effective data storage options based on requirements.
* Apply automated processes to ensure that data over time is stored on storage tiers that
minimize costs.
</details>

## Areas Covered
<details>
  <summary>Types</summary>

* Compute
* Cost management
* Database
* Disaster recovery
* High availability
* Management and governance
* Microservices and component decoupling
* Migration and data transfer
* Networking, connectivity, and content delivery
* Security
  
    ![image](https://user-images.githubusercontent.com/44328319/127173054-6721a4cd-ac53-492d-b62d-8432ddfb177b.png)
    ![image](https://user-images.githubusercontent.com/44328319/127173180-fc408fda-8d3d-449d-8466-d423e6b08440.png)
    ![image](https://user-images.githubusercontent.com/44328319/127173211-57e74be4-9e83-4072-bc7c-8d4b627b18ea.png)
    ![image](https://user-images.githubusercontent.com/44328319/127173332-c19dc17a-10ec-4b8a-bea8-97b25e15f5b2.png)
    ![image](https://user-images.githubusercontent.com/44328319/127173919-6098ecf4-fe43-40c9-a40a-26beb0c79b55.png)
  
* Serverless design principles
</details>
<details>
  <summary>AWS Services and Features</summary>

Analytics:
* Amazon Athena
* Amazon Elasticsearch Service (Amazon ES)
* [Amazon EMR](https://tutorialsdojo.com/amazon-emr/?src=udemy)
* AWS Glue
* [Amazon Kinesis](https://tutorialsdojo.com/amazon-kinesis/?src=udemy)
* Amazon QuickSight

AWS Billing and Cost Management:
* AWS Budgets
* Cost Explorer

Application Integration:
* Amazon Simple Notification Service (Amazon SNS)
* [Amazon Simple Queue Service SQS](https://aws.amazon.com/sqs/faqs/?ep=sec&sec=assoc_saa) and [Cheat Sheet](https://tutorialsdojo.com/amazon-sqs/?src=udemy)

Compute:
* [Amazon EC2](https://aws.amazon.com/ec2/faqs/?ep=sec&sec=assoc_saa) and [cheat sheet](https://tutorialsdojo.com/amazon-elastic-compute-cloud-amazon-ec2/%20?src=udemy)
  
  ![image](https://user-images.githubusercontent.com/44328319/127187878-0f66c1ea-2c5b-4306-b05d-d784fb96fcd5.png)

* AWS Elastic Beanstalk
* [Amazon Elastic Container Service (Amazon ECS)](https://tutorialsdojo.com/amazon-elastic-container-service-amazon-ecs/?src=udemy)
  ![image](https://user-images.githubusercontent.com/44328319/127787080-24716f97-6446-4be1-96d8-870fe66f80f2.png)

* [Amazon Elastic Kubernetes Service (Amazon EKS)](https://docs.aws.amazon.com/eks/latest/userguide/what-is-eks.html)
* [Elastic Load Balancing](https://tutorialsdojo.com/aws-elastic-load-balancing-elb/) (e.g. [comparison](https://tutorialsdojo.com/application-load-balancer-vs-network-load-balancer-vs-classic-load-balancer/)
  ![image](https://user-images.githubusercontent.com/44328319/130552242-0f10992e-9e83-4dc3-a4e6-c27cbf7ba1aa.png)

* AWS Fargate
* [AWS Lambda](https://tutorialsdojo.com/aws-lambda/?src=udemy)

Database:
* [Amazon Aurora](https://tutorialsdojo.com/amazon-aurora/)
* [Amazon DynamoDB](https://tutorialsdojo.com/amazon-dynamodb/?src=udemy) and [parition keys](https://aws.amazon.com/blogs/database/choosing-the-right-dynamodb-partition-key/) and [dynamo streams](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Streams.Lambda.Tutorial.html)
  ![image](https://user-images.githubusercontent.com/44328319/128016012-68be6308-4b90-48bc-bd29-9ee33e5263bd.png)

* [Amazon ElastiCache](https://tutorialsdojo.com/amazon-elasticache/?src=udemy)
* [Amazon RDS](https://aws.amazon.com/rds/faqs/?ep=sec&sec=assoc_saa) and [cheat sheet](https://tutorialsdojo.com/amazon-relational-database-service-amazon-rds/?src=udemy)
* [Amazon Redshift](https://tutorialsdojo.com/amazon-redshift/?src=udemy)

Management and Governance:
* [AWS Auto Scaling](https://tutorialsdojo.com/aws-auto-scaling/?src=udemy) and [FAQ Target Tracking Scaling](https://docs.aws.amazon.com/autoscaling/ec2/userguide/as-scaling-target-tracking.html)
* AWS Backup
* AWS CloudFormation
* [AWS CloudTrail](https://tutorialsdojo.com/aws-cloudtrail/?src=udemy)
  ![image](https://user-images.githubusercontent.com/44328319/130357361-712e8fad-f7e7-4f09-a179-e6ad97dba862.png)

* [Amazon CloudWatch](https://tutorialsdojo.com/amazon-cloudwatch/?src=udemy)
  ![image](https://user-images.githubusercontent.com/44328319/127785849-faf64975-c86b-4211-9598-e203bbfedba8.png)

* [AWS Config](https://tutorialsdojo.com/aws-config/?src=udemy)
* Amazon EventBridge (Amazon CloudWatch Events)
* AWS Organizations
* [AWS Resource Access Manager](https://aws.amazon.com/ram/)
* [AWS Systems Manager](https://tutorialsdojo.com/aws-systems-manager/?src=udemy) and [Parameter Store](https://aws.amazon.com/blogs/mt/the-right-way-to-store-secrets-using-parameter-store/)
* AWS Trusted Advisor

Migration and Transfer:
* AWS Database Migration Service (AWS DMS)
* [AWS DataSync](https://tutorialsdojo.com/aws-datasync/?src=udemy)
  ![image](https://user-images.githubusercontent.com/44328319/130419012-827b1989-9e43-4c6d-b38b-5ad9687d959b.png)

* AWS Migration Hub
* AWS Server Migration Service (AWS SMS)
* AWS Snowball
  ![image](https://user-images.githubusercontent.com/44328319/130419974-915fbb09-cce1-4f1a-a1d5-4eb64bc0ba3a.png)

* AWS Transfer Family
![image](https://user-images.githubusercontent.com/44328319/130579687-c0b43543-7493-4e67-b419-5e189eb58e27.png)

Networking and Content Delivery:
* [Amazon API Gateway](https://tutorialsdojo.com/amazon-api-gateway/?src=udemy) and [FAQ Throttling Limits](https://aws.amazon.com/api-gateway/faqs/#Throttling_and_Caching)
* [Amazon CloudFront](https://tutorialsdojo.com/amazon-cloudfront/?src=udemy) and [private signed cookies](https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/private-content-signed-cookies.html)
* AWS Direct Connect
* AWS Global Accelerator
* [Amazon Route 53](https://aws.amazon.com/route53/faqs/?ep=sec&sec=assoc_saa) and [cheat sheet](https://tutorialsdojo.com/amazon-route-53/)
  ![image](https://user-images.githubusercontent.com/44328319/130411297-10c7b9d1-1658-4265-81eb-159c6f0e635e.png)
  ![image](https://user-images.githubusercontent.com/44328319/130411808-b7be9669-32b9-428a-ba02-adc6b4914169.png)


* AWS Transit Gateway
* [Amazon VPC](https://aws.amazon.com/vpc/faqs/?ep=sec&sec=assoc_saa) and [cheat sheet](https://tutorialsdojo.com/amazon-vpc/?src=udemy)
  
  ![image](https://user-images.githubusercontent.com/44328319/127172005-1313ef3b-1142-4a35-b0b9-85176882acf6.png)


Security, Identity, and Compliance:
* AWS Certificate Manager (ACM)
* [AWS Directory Service](https://tutorialsdojo.com/aws-directory-service/?src=udemy)
* Amazon GuardDuty
* [AWS Identity and Access Management (IAM)](https://tutorialsdojo.com/aws-identity-and-access-management-iam/?src=udemy) and [IAM DB AUTH](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/UsingWithRDS.IAMDBAuth.html)
* Amazon Inspector
* [AWS Key Management Service (AWS KMS)](https://tutorialsdojo.com/aws-key-management-service-aws-kms/?src=udemy)
* [Amazon Macie](https://tutorialsdojo.com/amazon-macie/?src=udemy)
* AWS Secrets Manager
* [AWS Shield](https://tutorialsdojo.com/aws-shield/?src=udemy)
* AWS Single Sign-On
* [AWS WAF](https://tutorialsdojo.com/aws-waf/?src=udemy)

Storage:
* [Amazon Elastic Block Store (Amazon EBS)](https://tutorialsdojo.com/amazon-ebs/%20?src=udemy)
  ![image](https://user-images.githubusercontent.com/44328319/127786614-4609eafa-212f-4be1-bc87-28c0c41004f5.png)
  ![image](https://user-images.githubusercontent.com/44328319/127188081-4b0bab60-a2fd-4bcc-b377-61c71b7253a7.png)
  ![image](https://user-images.githubusercontent.com/44328319/127188194-ff4e01c7-feed-4948-9632-c99b3621748f.png)

* [Amazon Elastic File System (Amazon EFS)](https://tutorialsdojo.com/amazon-efs/?src=udemy)
* [Amazon FSx](https://tutorialsdojo.com/amazon-fsx/?src=udemy)
* [Amazon S3](https://aws.amazon.com/s3/faqs/?ep=sec&sec=assoc_saa) and [cheat sheet](https://tutorialsdojo.com/amazon-s3/?src=udemy) and [s3 transfer acceleration](https://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html)
  ![image](https://user-images.githubusercontent.com/44328319/130579086-5f87e888-4227-4e4c-b090-2523bd6edca0.png)
  ![image](https://user-images.githubusercontent.com/44328319/130578771-54dc60ae-d06c-4309-82e6-2e40fc30022e.png)

* [Amazon S3 Glacier](https://aws.amazon.com/s3/storage-classes/)
  ![image](https://user-images.githubusercontent.com/44328319/130414197-0611c541-118b-445f-8cd9-68b9af6789a2.png)

* [AWS Storage Gateway](https://tutorialsdojo.com/aws-storage-gateway/?src=udemy)
  ![image](https://user-images.githubusercontent.com/44328319/130579234-e03492e2-4318-4c25-9773-1727b922de5a.png)

</details>

## CLI Helpful Commands
<details>
  <summary>Expand</summary>
  
* ```aws configure```
* Copies file from local to bucket```aws s3 cp <path> s3://<bucket>```
* List buckets```aws s3 ls```
* List Bucket Content: ```aws s3 ls s3://<bucket>```
* Create s3 bucket ```aws s3api create-bucket --bucket <bucketname> --region us-east-1```
* grab your environment variables from cli ```env | grep ^AWS```
* What is the policies attached to that user ```aws iam list-attached-user-policies --user-name=$AWS_ACCOUNT_USERNAME```
* Create iam user ```aws iam create-user --user-name root-for-vault```
* Attach policy ```aws iam attach-user-policy --user-name root-for-vault --policy-arn arn:aws:iam::${AWS_ACCOUNT_ID}:policy/vault-root```
* Create access key and secret passing to txt for temp use ```aws iam create-access-key --user-name root-for-vault | tee root-for-vault-keys.txt```
* Set default region ```export AWS_DEFAULT_REGION=us-east-1```
* Create VPC ```aws ec2 create-default-vpc```
* Run EC2 ```aws ec2 run-instances --image-id <amiid> --instance-type <ec2type> --count 1```
* List RDS ```aws rds describe-db-instances```
* Grab metadata from instance ```curl http://169.254.169.254/latest/meta-data/``` ```wget http://169.254.169.254/latest/meta-data/```
* Grab userdata from instance ```curl http://169.254.169.254/latest/user-data/```
* List lambda functions ```aws lambda list-functions --max-items 10```  [Full list of lambda cli ](https://docs.aws.amazon.com/cli/latest/reference/lambda/index.html)
* Invoke Lambda ```aws lambda invoke \
    --function-name my-function \
    --payload '{ "name": "Bob" }' \
    response.json```
* Delete an S3 bucket and all its contents with just one command 
`aws s3 rb s3://bucket-name -force`
* Copy a directory and its subfolders from your PC to Amazon S3 
`aws s3 cp MYFolder s3://bucket-name -recursive [-region us-west-2]`
* Display subsets of all available ec2 images 
`aws ec2 describe-images | grep ubuntu`
* List users in a different format 
`aws iam list-users --output table`
* Get credentialed IAM reports from CLI `aws iam generate-credential-report` and read it `aws iam get-credential-report --output text | base64 --decode >> credentialreport.csv`
* List the sizes of an S3 bucket and its contents 
`aws s3api list-objects --bucket BUCKETNAME --output json --query " 
[sum(Contents[].Size), length(Contents[])]"`
* Move S3 bucket to a different location 
`aws s3 sync s3://oldbucket s3://newbucket --source-region us-west-l 
--region us-west-2`
* List users by ARN 
`aws iam list-users --output json | jq -r .Users[].Arn`
* List all of your instances that are currently running
`aws ec2 describe-instances --filters Name=instance-state-name,Values=running --query 'Reservations[*].Instances[].[InstanceId,State,PublicIpAddress, Tags[?Key==`Name`]]' --region us-east-1 --output json | jq`
`aws ec2 describe-instances --filters Name=instance-state-name,Values=running --region us-east-1 --output table`
* Other ways to pass input parameters to the AWS CLI with JSON 
`aws iam put-user-policy --user-name AWS-Cli-Test --policy-name 
Power-Access --policy-document { "Statement":[{ "Effect": 
"Allow" , "NotAction":"iam:*", "Resource": "*"} ] }`
</details>
  
## Resources
<details>
    <summary>Expand</summary>
  
* [Tutorial Dojo Study Guide](https://tutorialsdojo.com/aws-certified-solutions-architect-associate-saa-c02/?src=udemy) and [Cheat Sheets](https://tutorialsdojo.com/aws-cheat-sheets/)
* [Notes Doc](https://github.com/MattN-HB/aws-solutions-architect/blob/main/AWS%20Certified%20Solutions%20Architect.pdf)
* [Great Medium Article on how to crack it](https://medium.com/javarevisited/top-5-aws-training-courses-to-crack-amazon-web-service-solutions-architect-associate-certification-3f4affa8f660)
* [AWS Whitepapers](http://aws.amazon.com/whitepapers/)
* [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/)
* [AWS Training](http://aws.amazon.com/training) and [Free Training](https://www.aws.training/learningobject/curriculum?id=20685&ep=sec&sec=assoc_saa)
* [Acloudguru training](https://acloudguru.com/course/aws-certified-solutions-architect-associate-saa-c02)
* [Udemy course](https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c02/?ranMID=39197&ranEAID=CuIbQrBnhiw&ranSiteID=CuIbQrBnhiw-9pVf0yrvMcU_MIPaorYTQQ&utm_source=aff-campaign&utm_medium=udemyads&LSNPUBID=CuIbQrBnhiw)
* [Free Practice Exams](https://www.knowledgehut.com/practice-tests/aws-solutions-architect-associate) ,[25 questions](https://awscoach.net/architect-associate-questions/) and [Dump Practice Exams](https://github.com/MattN-HB/aws-solutions-architect/tree/main/PracticeExams) and [$20 Practice Exam Thru Cert Center](https://www.certmetrics.com/amazon/candidate/exam_scheduling.aspx)
* [Amazing 6 practice exams $29.99 with video and thorough study guides/explanations](https://www.udemy.com/course/aws-certified-solutions-architect-associate-amazon-practice-exams-saa-c02/?LSNPUBID=JVFxdTr9V80&ranEAID=JVFxdTr9V80&ranMID=39197&ranSiteID=JVFxdTr9V80-f5zcy9zHHnUSBI.ZVgWHGA&utm_medium=udemyads&utm_source=aff-campaign)
* [Flashcards](https://quizlet.com/125872081/aws-solutions-architect-flash-cards/)
* [Main Cert Page](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
* [AWS Cert Center](https://www.certmetrics.com/amazon/default.aspx)
* [All Official AWS Cert Past Exams](https://aws.psiexams.com/#/dashboard/compact-dashboard)
* [AWS Cert Prep Center](https://aws.amazon.com/certification/certification-prep/?cta=saa_examprep)
* [All FAQs](https://aws.amazon.com/faqs/?ep=sec&sec=assoc_saa)
* [CLI S3 cheat sheet](https://acloudguru.com/blog/engineering/aws-s3-cheat-sheet)
* [Boto3 SNS Doc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Client.publish)
* [EFS vs S3 Cheat Sheet](https://tutorialsdojo.com/amazon-s3-vs-ebs-vs-efs/?src=udemy)
* [Aurora Custom Endpoints](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.Overview.Endpoints.html)
* [Aurora Global Database](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-global-database.html)
* [Aurora Serverless DB](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless.how-it-works.html)
* [MQ](https://tutorialsdojo.com/amazon-mq/?src=udemy)
* [Nat Gateway Comparison](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat-comparison.html)
* [Aurora plus lambda](https://aws.amazon.com/blogs/database/capturing-data-changes-in-amazon-aurora-using-aws-lambda/)
 </details>  
  
## My Personal Cheat Sheet / Takeways
 <details>
    <summary>Expand</summary>
   
 * whole vpc use nacl not sec group..sec group to instances
   ![image](https://user-images.githubusercontent.com/44328319/130420204-178bb2e1-c8af-4751-bcc1-1f457a2a9d9b.png)
 * NACL default open but if you restrict you'll need set ephermal ports. Remember if meets rule first it be followed!
  ![image](https://user-images.githubusercontent.com/44328319/130572090-ebce8256-0b31-4d28-acec-3df97bd4f44a.png)
  ![image](https://user-images.githubusercontent.com/44328319/130578145-9e496d21-793f-4f2c-ae4c-2611ff3fc441.png)

 * Subnets: Below are the important points you have to remember about subnets:
   * Each subnet maps to a single Availability Zone. 
   * Every subnet that you create is automatically associated with the main route table for the VPC.
   * If a subnet's traffic is routed to an Internet gateway, the subnet is known as a public subnet.
 * Create an Auto Scaling group of EC2 instances and set the minimum capacity to 4 and the maximum capacity to 6. Deploy 2 instances in Availability Zone A and another 2 instances in Availability Zone B.
 * You are limited to running On-Demand Instances per your vCPU-based On-Demand Instance limit, purchasing 20 Reserved Instances, and requesting Spot Instances per your dynamic Spot limit per region.
 * ec2 billing by state:
   ![image](https://user-images.githubusercontent.com/44328319/130574527-822b56e4-390f-48ba-ad14-c4b765923095.png)
   ![image](https://user-images.githubusercontent.com/44328319/130574324-4a7cf0e4-dd15-4812-bb77-bfe4960a3efa.png)

 * elastic cache and dynamo db store session mgmt
 * ElastiCache improves the performance of your database through **caching query results.**
 * iam role plus ad connector (when in doubt IAM is your friend)
 * Cookies (keep url) and signed URL if don't mind diff url. If don't want use s3 links use cookies and Restrict access to files in the origin by creating an origin access identity (OAI) and give it permission to read the files in the bucket.
 * S3 transfer acceleration 
   ![image](https://user-images.githubusercontent.com/44328319/130580704-08e1f0cd-3b5e-478d-a190-c5ca1bafd01f.png)

 * EMR = big data / analyze
 * Route 53 failover (active active = majority) Two types of failover configurations
   * Active-Active Failover – all the records that have the same name, the same type, and the same routing policy are active unless Route 53 considers them unhealthy. Use this failover configuration when you want all of your resources to be available the majority of the time.
   * Active-Passive Failover – use this failover configuration when you want a primary resource or group of resources to be available the majority of the time and you want a secondary resource or group of resources to be on standby in case all the primary resources become unavailable. When responding to queries, Route 53 includes only the healthy primary resources.
 * Route53 geopromixity for user location
   ![image](https://user-images.githubusercontent.com/44328319/130551946-882a42c5-90a2-4844-b93c-301f7aebeb46.png)
   ![image](https://user-images.githubusercontent.com/44328319/130551988-9f5de612-2957-450e-b35d-319d9fbe5148.png)
   ![image](https://user-images.githubusercontent.com/44328319/130552025-b5a11c02-951c-41c7-9fec-604e8e4667d9.png)

 * S3 web hosting cheaper
 * s3 **Expedited retrievals** allow you to quickly access your data when occasional urgent requests and **Provisioned capacity** ensures that your retrieval capacity for expedited retrievals 
 * ssd = small,IOPS while HDD = Throughput, large sequential
   ![image](https://user-images.githubusercontent.com/44328319/130420548-3572f331-f1d4-497d-99a0-14f68f93babc.png)

 * parameter store ecs + doesn't by default rotate keys. Secrets manager if enabled rotates keys.
 * A and AAAA = route53 aliases to alb
 * Nlb can assign eip not alb
   ![image](https://user-images.githubusercontent.com/44328319/130552183-41a03540-6677-40a5-bb19-87fc065c4ffd.png)

 * "Open source" container = EKS
 * aws storage gateway = small data transfer and **caching**
   ![image](https://user-images.githubusercontent.com/44328319/130579498-de043d5c-7949-4c5c-9435-b4dcfb1e790c.png)

 * aws datasyc = large data transfer
 * when bandwith slow and need 250TB use snowball. As a rule of thumb, if it takes more than one week to upload your data to AWS using the spare capacity of your existing Internet connection, then you should consider using Snowball. For example, if you have a 100 Mb connection that you can solely dedicate to transferring your data and need to transfer 100 TB of data, it takes more than 100 days to complete data transfer over that connection. You can make the same transfer by using multiple Snowballs in about a week.
   ![image](https://user-images.githubusercontent.com/44328319/130420000-d648c685-377a-4dfe-bb64-90a81c91b00e.png)

 * dynamo issues check shard due to **dynamo autoscales automatically UNLESS created by CLI**
   ![image](https://user-images.githubusercontent.com/44328319/130420964-5cbb29a8-1840-4fc0-b5ba-f1adfb381cf7.png)
 * dynamo = scalable and key-value
   ![image](https://user-images.githubusercontent.com/44328319/130421808-1faf0869-2673-41e8-831d-c33cae24e877.png)

 * SQS 1min to 14 day retention with 120K standard queue limit and 20k fifo
 * Only FIFO queues can preserve the order of messages and not standard queues. FIFO provides exact one delivery. Standard at least once.
 * DLM and backups for auto snapshots
 * RDS Failover happens CNAME points to the standby instance
   ![image](https://user-images.githubusercontent.com/44328319/130422152-0f866063-b6af-4b2e-83af-d6482527e50c.png)
   
 * DDOS prevention >Create a rate-based web ACL rule using AWS WAF and associate it with Amazon CloudFront.
 * cross site scripting and sql injection enabled in waf
 * Autoscale cooldown period = 300sec and new launch config only for changing AMI (target groups choose what instances)
 * Oldest configured ec2 unless  
![image](https://user-images.githubusercontent.com/44328319/127865099-7c4f5f58-7883-4ca6-ba14-f7e33b75370d.png)

 * Read replicas
![image](https://user-images.githubusercontent.com/44328319/128017372-39a557c5-c26d-4933-b63e-903f01494bce.png)
![image](https://user-images.githubusercontent.com/44328319/130573417-d51f08c9-8704-4745-93e0-27bda15bc2d6.png)


 * only from corporate ips to bastion in public subnet    
![image](https://user-images.githubusercontent.com/44328319/130413393-9dd1cb98-e642-43a7-851e-864f1a0e5e88.png)
   
 * VPC public subnet to VPC direct connected how to connect...
   ![image](https://user-images.githubusercontent.com/44328319/130428655-55684d2a-b610-45b4-9b16-2626be491af8.png)

 * Decouple services with swf and sqs
 * Cloud formation: Use the **CreationPolicy attribute when you want to wait on resource** configuration actions before stack creation proceeds.
 * Redshift = bigdata and business intelligence analytics
 * Amazon Kinesis Data Firehose is the easiest way to load streaming data into data stores and analytics tools (e.g. splunk, elk,s3)
   
 </details>  
