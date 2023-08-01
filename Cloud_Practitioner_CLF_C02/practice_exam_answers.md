Incorrect. Amazon Inspector is an automated security assessment service that helps improve the security and compliance of applications deployed on Amazon EC2 instances. Amazon Inspector does not perform S3 data classification and automatic discovery.

Correct. Macie is an automated security assessment service that helps improve the security and compliance of applications deployed on AWS.

Incorrect. GuardDuty is a threat detection service that continuously monitors for malicious activity and unauthorized behavior to protect your AWS accounts and workloads. GuardDuty does not perform S3 data classification.

Incorrect. Secrets Manager helps you protect secrets needed to access your applications, services, and IT resources. Secrets Manager does not perform S3 data classification and automatic discovery.

|------------------------------------

Incorrect. CodeArtifact is a managed artifact repository service that stores and shares software that is ready for deployment. CodeArtifact is not a source code management service.

Incorrect. CodeBuild is a service that helps users to automatically compile source code, run unit tests, and produce software packages that are ready for deployment. CodeBuild is not a code management service.

Incorrect. CodePipeline is a service that manages the movement of code between the individual services. CodePipeline is not a source code storage service.

Correct. CodeCommit is a source code version control service. CodeCommit helps users store and manage developers' source code in AWS.

|------------------------------------

Incorrect. AWS Cloud Map creates and maintains a map of backend services. AWS Cloud Map will not address governance or payment consolidation.

Correct. Organizations provides centralized governance and billing for an AWS environment, including multiple accounts.

Incorrect. OpsCenter provides a central location for IT professionals to view, investigate, and resolve operational work items. OpsCenter does not consolidate billing.

Incorrect. This solution consolidates the billing in a report, but it will work only for the individual accounts (without cross-account billing). This solution does not address central governance.

|------------------------------------

Incorrect. Client VPN is a managed client-based VPN service that gives you the ability to securely access your AWS resources and the resources in your on-premises network. With Client VPN, you can access your resources from any location through an OpenVPN-based VPN client. You would use Client VPN to connect individual laptops to AWS, not an entire data center.

Incorrect. Amazon Connect is an omnichannel cloud contact center that helps you provide superior customer service at a lower cost. Amazon Connect provides a seamless experience across voice and chat for your customers and agents. Amazon Connect is not a service that connects an on-premises network to AWS.

Correct. Direct Connect links your internal network to a Direct Connect location through a standard Ethernet fiber-optic cable. One end of the cable connects to your router. The other end of the cable connects to a Direct Connect router. AWS Direct Connect is consistent and private because your company is the only user of the cable.

Incorrect. Site-to-Site VPN creates an encrypted network path between your on-premises network and your AWS Cloud network. This connection uses the internet, so you cannot expect consistency. Even though the traffic is encrypted, the connection is not private because the internet is a shared resource.

|------------------------------------

Correct. Amazon S3 is an object storage service.

Correct. Amazon S3 is a durable object storage service.

|------------------------------------

Correct. The deployment of the EC2 instances in multiple Availability Zones prevents a single point of failure. Availability Zones are designed for physical redundancy and to provide resilience with uninterrupted performance.

Correct. If you host all your instances in a single location that is affected by a failure, none of your instances would be available. Availability Zones are designed for physical redundancy and to provide resilience with uninterrupted performance.

|------------------------------------

Incorrect. Reserved Instances reserve some capacity for your use at any time. Reserved Instances can sometimes give you a discount. However, this capacity is not unused capacity.

Incorrect. On-Demand Instances are the default purchase option and are immediately available. On-Demand Instances are not discounted.

Incorrect. Dedicated Instances run in VPCs on hardware dedicated to that individual customer and are often used when there are licensing or compliance constraints. Dedicated Instances are not discounted.

Correct. With Spot Instances, you can access unused EC2 capacity. Spot Instances can be discounted.

|------------------------------------

Incorrect. Amazon Transcribe is a service that uses machine learning to convert audio data to text. Amazon Transcribe is not a text-to-speech conversion service.

Correct. Amazon Polly is a machine learning service that converts text to speech. This service provides the ability to read text out loud.

Incorrect. Amazon Translate is a machine learning language translation service. Amazon Translate is not a text-to-speech conversion service.

Incorrect. Amazon Textract is a machine learning service that can extract text from scanned documents. Amazon Textract is not a text-to-speech conversion service.

|------------------------------------

Incorrect. Elastic Beanstalk is a service to deploy and scale web applications and services developed with common programming languages on automatically deployed infrastructure with capacity management, load balancing, auto scaling, and monitoring. Elastic Beanstalk makes it easier to provision and support an application. Elastic Beanstalk does not reduce website latency.

Incorrect. DAX is used to reduce response times from a DynamoDB table from single-digit milliseconds to microseconds. DynamoDB tables cannot host static websites.

Incorrect. Route 53 is a highly available and scalable DNS web service. The three main functions of Route 53 are registering domain names, routing internet traffic to the resources for your domain, and checking the health of those resources. Route 53 can direct traffic to S3 buckets. But because the question describes only one S3 bucket, Route 53 would have only one potential route and could not reduce latency.

Correct. CloudFront is a web service that speeds up the distribution of your static and dynamic web content, such as .html, .css, .js, and image files, to your users. Content is cached in edge locations. Content that is repeatedly accessed can be served from the edge locations instead of the source S3 bucket.

|------------------------------------

Correct. The use of Regions around the world will improve an application's global performance and reduce latency for users.

Correct. CloudFront is a content delivery network (CDN) service that securely delivers data, videos, applications, and APIs to global customers with low latency and high transfer speeds.

Incorrect. Amazon Comprehend is a natural language processing (NLP) service that uses machine learning to find insights and relationships in text. Amazon Comprehend does not translate text.

Incorrect. A load balancer accepts incoming traffic from clients and routes requests to its registered targets (such as EC2 instances) in one or more Availability Zones. However, a load balancer does not accept targets across Regions.

|------------------------------------

Correct. Trusted Advisor checks security groups for rules that allow unrestricted access to a resource. Unrestricted access increases opportunities for malicious activity, such as hacking, denial-of-service attacks, or loss of data. 

Incorrect. AWS Config continuously monitors and records changes to your AWS resources, but it does not identify security groups that allow unrestricted access.

Incorrect. CloudWatch is a monitoring service that collects and tracks metrics for AWS resources. It does not identify security groups that allow unrestricted access.

Incorrect. CloudTrail provides an audit record of API calls. It does not identify security groups that allow unrestricted access.

|------------------------------------

Correct. Lambda charges are dependent on the amount of time it takes to run the code.

Incorrect. The number of versions of a specific Lambda function does not contribute to the cost. You are charged based on the number of requests for your Lambda functions and the duration of time it takes for your code to run.

Correct. Lambda charges are dependent on the number of requests for your Lambda functions.

Incorrect. The programming language that is used to create the Lambda function does not contribute to the cost. You are charged based on the number of requests for your Lambda functions and the duration of time it takes for your code to run.

Incorrect. There is no charge based on the number of functions in an AWS account. You are charged based on the number of requests for your Lambda functions and the duration of time it takes for your code to run.

|------------------------------------

Incorrect. The Enterprise Support plan provides phone support, but it is not the minimum plan to do so.

Correct. You can call or chat with technical support by using the Business Support plan or the Enterprise Support plan. The Business Support plan is the minimum plan that provides this feature.

Incorrect. The Developer Support plan allows only email creation of support tickets and does not provide phone support.

Incorrect. The Basic Support plan provides customer support for non-technical issues, such as increases in service quotas. However, the Basic Support plan does not provide technical support.

|------------------------------------

Incorrect. Global Accelerator is a networking service that improves the performance of your users’ network traffic by up to 60%. Global Accelerator uses the AWS global network infrastructure. Global Accelerator is not a relational database.

Incorrect. DynamoDB is a fully managed NoSQL database service. DynamoDB provides fast and predictable performance with seamless scalability. However, DynamoDB is not a relational database.

Correct. Aurora is a MySQL- and PostgreSQL-compatible relational database built for the cloud. Aurora combines the performance and availability of traditional enterprise databases with the simplicity and cost-effectiveness of open source databases.

Incorrect. Amazon EBS is an easy-to-use, high-performance block-storage service. You can use Amazon EBS with Amazon EC2 for both throughput- and transaction-intensive workloads at any scale. You can run a database on Amazon EC2 instances and use Amazon EBS for the storage for that database. However, Amazon EBS by itself is not a relational database.

|------------------------------------

Correct. CloudWatch monitors your AWS resources and the applications that you run on AWS in real time. You can use CloudWatch with AWS CloudTrail to monitor and receive alerts about console sign-in events that involve the AWS account root user.

Incorrect. You can use AWS Config to assess, audit, and evaluate the configurations of your AWS resources. AWS Config cannot alert you about console sign-in events that involve the AWS account root user.

Incorrect. You can use Trusted Advisor for real-time guidance to help you provision your resources according to AWS best practices. Trusted Advisor cannot alert you about console sign-in events that involve the AWS account root user.

Incorrect. With IAM, you can manage access to AWS services and resources securely. IAM cannot alert you about console sign-in events that involve the AWS account root user.

|------------------------------------

Incorrect. Direct Connect links your internal network to a Direct Connect location over a network connection. One end of the connection attaches to your on-premises router. The other end connects to a Direct Connect router. With this connection, you can bypass the ISPs in your network path. However, the company must use an existing internet connection in this scenario.

Incorrect. Amazon Connect is an omnichannel cloud contact center. Amazon Connect helps you provide customer service at a low cost. Amazon Connect uses an omnichannel design to provide a seamless experience across voice and chat for your customers and agents. Amazon Connect does not provide a network connection.

Incorrect. CloudFront is a web service that speeds up the distribution of your static and dynamic web content to your users. CloudFront delivers your content through a worldwide network of data centers known as edge locations. When a user requests content that you serve through CloudFront, the request is routed to the edge location that provides the lowest latency. However, CloudFront does not provide a network connection.

Correct. Site-to-Site VPN creates an encrypted network path between your on-premises network and your AWS Cloud network. This connection between your on-premises network and your AWS Cloud network uses the internet. 

|------------------------------------

Incorrect. AWS DMS can be used to migrate data from an on-premises database to a database in AWS. However, AWS DMS does not migrate the actual server to an EC2 instance.

Incorrect. Migration Hub is a service that helps plan and track application migrations. Migration Hub does not perform system migrations.

Correct. AWS MGN is an automated lift-and-shift solution. This solution can migrate physical servers and any databases or applications that run on them to EC2 instances in AWS.

Incorrect. Application Discovery Service collects information about the usage and configuration of on-premises servers to help plan a migration to AWS. Application Discovery Service does not actually perform migration operations.

|------------------------------------

Incorrect. The performance efficiency pillar includes the ability to use computing resources efficiently to meet system requirements, and to maintain that efficiency as demand changes and technologies evolve. The use of multiple Availability Zones does not increase performance efficiency.

Correct. The reliability pillar includes the ability of a workload to perform its intended function correctly and consistently when it is expected to do so. The deployment of Amazon RDS in multiple Availability Zones supports the goal of reliability because it reduces single points of failure.

Incorrect. The cost optimization pillar includes the ability to run systems to deliver business value at the lowest price point. Reliability is supported by using resources in multiple Availability Zones. The use of multiple Availability Zones for resources will increase cost.

Incorrect. The security pillar includes the ability to protect data, systems, and assets to take advantage of cloud technologies to improve a company's security. The use of multiple Availability Zones for resources does not make an application more secure.

|------------------------------------

Incorrect. AWS provides Lambda as a service. The customer does not have to patch the operating system.

Incorrect. AWS provides Amazon RDS as a service. AWS manages patches for the Amazon RDS engine. The customer can choose a time window to install patches.

Incorrect. AWS does not allow access to data centers. A customer can take a virtual tour of a data center to understand the security measures and controls. Customers cannot visit data centers in person.

Correct. AWS provides AWS Identity and Access Management (IAM) as a service. The customer defines IAM users and the access policies that apply to those users.

Correct. The customer determines access permissions to S3 buckets that the customer owns.  

|------------------------------------

Correct. Programmatic access requires an access key ID and a secret access key that can be assigned to an AWS user.

Incorrect. A primary key is a feature used in database management. It does not grant AWS account access.

Correct. Programmatic access requires an access key ID and a secret access key that can be assigned to an AWS user.

Incorrect. A user ID is used for IAM security credentials, but not for programmatic access.

Incorrect. A secondary key is a feature used in database management. It does not grant AWS account access.