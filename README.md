# aws-solutions-architect
This repo is a guide to taking solutions architect associate cert in 2021. The main [overview of the exam](https://github.com/MattN-HB/aws-solutions-architect/blob/main/AWS-Certified-Solutions-Architect-Associate_Exam-Guide.pdf) and [AWS official site](https://aws.amazon.com/certification/certified-solutions-architect-associate/)

## Domain Breakdown [Training by Domain](https://www.aws.training/Details/Curriculum?id=20685&ep=sec&sec=assoc_saa)
<details>
  <summary>Domain 1: Design Resilient Architectures 30%</summary>

1.1 Design a multi-tier architecture solution
* Determine a solution design based on access patterns.
* Determine a scaling strategy for components used in a design.
* Select an appropriate database based on requirements.
* Select an appropriate compute and storage service based on requirements.

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

3.2 Design secure application tiers

* Given traffic control requirements, determine when and how to use security groups and
network ACLs.
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
* Amazon EMR
* AWS Glue
* Amazon Kinesis
* Amazon QuickSight

AWS Billing and Cost Management:
* AWS Budgets
* Cost Explorer

Application Integration:
* Amazon Simple Notification Service (Amazon SNS)
* [Amazon Simple Queue Service SQS](https://aws.amazon.com/sqs/faqs/?ep=sec&sec=assoc_saa)

Compute:
* [Amazon EC2](https://aws.amazon.com/ec2/faqs/?ep=sec&sec=assoc_saa)
  
  ![image](https://user-images.githubusercontent.com/44328319/127187878-0f66c1ea-2c5b-4306-b05d-d784fb96fcd5.png)

* AWS Elastic Beanstalk
* Amazon Elastic Container Service (Amazon ECS)
* Amazon Elastic Kubernetes Service (Amazon EKS)
* Elastic Load Balancing
* AWS Fargate
* AWS Lambda

Database:
* Amazon Aurora
* Amazon DynamoDB
* Amazon ElastiCache
* [Amazon RDS](https://aws.amazon.com/rds/faqs/?ep=sec&sec=assoc_saa)
* Amazon Redshift

Management and Governance:
* AWS Auto Scaling
* AWS Backup
* AWS CloudFormation
* AWS CloudTrail
* Amazon CloudWatch
* AWS Config
* Amazon EventBridge (Amazon CloudWatch Events)
* AWS Organizations
* AWS Resource Access Manager
* AWS Systems Manager
* AWS Trusted Advisor

Migration and Transfer:
* AWS Database Migration Service (AWS DMS)
* AWS DataSync
* AWS Migration Hub
* AWS Server Migration Service (AWS SMS)
* AWS Snowball
* AWS Transfer Family

Networking and Content Delivery:
* Amazon API Gateway
* Amazon CloudFront
* AWS Direct Connect
* AWS Global Accelerator
* [Amazon Route 53](https://aws.amazon.com/route53/faqs/?ep=sec&sec=assoc_saa)
* AWS Transit Gateway
* [Amazon VPC](https://aws.amazon.com/vpc/faqs/?ep=sec&sec=assoc_saa)
  
  ![image](https://user-images.githubusercontent.com/44328319/127172005-1313ef3b-1142-4a35-b0b9-85176882acf6.png)


Security, Identity, and Compliance:
* AWS Certificate Manager (ACM)
* AWS Directory Service
* Amazon GuardDuty
* AWS Identity and Access Management (IAM)
* Amazon Inspector
* AWS Key Management Service (AWS KMS)
* Amazon Macie
* AWS Secrets Manager
* AWS Shield
* AWS Single Sign-On
* AWS WAF

Storage:
* Amazon Elastic Block Store (Amazon EBS)
  
  ![image](https://user-images.githubusercontent.com/44328319/127188081-4b0bab60-a2fd-4bcc-b377-61c71b7253a7.png)
  ![image](https://user-images.githubusercontent.com/44328319/127188194-ff4e01c7-feed-4948-9632-c99b3621748f.png)
  ![image](https://user-images.githubusercontent.com/44328319/127188330-3a36f035-96d3-4f0a-b154-7a77d17cbc70.png)

* Amazon Elastic File System (Amazon EFS)
* Amazon FSx
* [Amazon S3](https://aws.amazon.com/s3/faqs/?ep=sec&sec=assoc_saa)
* Amazon S3 Glacier
* AWS Storage Gateway
</details>

## Scoring
* 100 - 1000 with minimum 720
* scaled scoring model
* 15 unscored questions that do not affect your score
* Unanswered questions are scored as incorrect; there is no penalty for guessing
* Multiple-choice: Has one correct response and three incorrect responses (distractors).
* Multiple-response: Has two or more correct responses out of five or more options

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
</details>
  
## Resources
* [Notes Doc](https://github.com/MattN-HB/aws-solutions-architect/blob/main/AWS%20Certified%20Solutions%20Architect.pdf)
* [Great Medium Article on how to crack it](https://medium.com/javarevisited/top-5-aws-training-courses-to-crack-amazon-web-service-solutions-architect-associate-certification-3f4affa8f660)
* [AWS Whitepapers](http://aws.amazon.com/whitepapers/)
* [AWS Well-Architected](https://aws.amazon.com/architecture/well-architected/)
* [AWS Training](http://aws.amazon.com/training) and [Free Training](https://www.aws.training/learningobject/curriculum?id=20685&ep=sec&sec=assoc_saa)
* [Acloudguru training](https://acloudguru.com/course/aws-certified-solutions-architect-associate-saa-c02)
* [Udemy course](https://www.udemy.com/course/aws-certified-solutions-architect-associate-saa-c02/?ranMID=39197&ranEAID=CuIbQrBnhiw&ranSiteID=CuIbQrBnhiw-9pVf0yrvMcU_MIPaorYTQQ&utm_source=aff-campaign&utm_medium=udemyads&LSNPUBID=CuIbQrBnhiw)
* [Free Practice Exams](https://www.knowledgehut.com/practice-tests/aws-solutions-architect-associate) ,[25 questions](https://awscoach.net/architect-associate-questions/) and [Dump Practice Exams](https://github.com/MattN-HB/aws-solutions-architect/tree/main/PracticeExams) and [$20 Practice Exam Thru Cert Center](https://www.certmetrics.com/amazon/candidate/exam_scheduling.aspx)
* [6 practice exams $29.99](https://www.udemy.com/course/aws-certified-solutions-architect-associate-amazon-practice-exams-saa-c02/?LSNPUBID=JVFxdTr9V80&ranEAID=JVFxdTr9V80&ranMID=39197&ranSiteID=JVFxdTr9V80-f5zcy9zHHnUSBI.ZVgWHGA&utm_medium=udemyads&utm_source=aff-campaign)
* [Flashcards](https://quizlet.com/125872081/aws-solutions-architect-flash-cards/)
* [Main Cert Page](https://aws.amazon.com/certification/certified-solutions-architect-associate/)
* [AWS Cert Center](https://www.certmetrics.com/amazon/default.aspx)
* [All Official AWS Cert Past Exams](https://aws.psiexams.com/#/dashboard/compact-dashboard)
* [AWS Cert Prep Center](https://aws.amazon.com/certification/certification-prep/?cta=saa_examprep)
* [All FAQs](https://aws.amazon.com/faqs/?ep=sec&sec=assoc_saa)
* [CLI S3 cheat sheet](https://acloudguru.com/blog/engineering/aws-s3-cheat-sheet)
* [Boto3 SNS Doc](https://boto3.amazonaws.com/v1/documentation/api/latest/reference/services/sns.html#SNS.Client.publish)
