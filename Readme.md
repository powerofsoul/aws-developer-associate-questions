### Which of the following are good use cases for how Amazon ElastiCache can help an application? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Improve latency and throughput for read-heavy application workloads.
- [x] Improve performance of compute-intensive applications.   

</details>

0.   Improve the performance of S3 PUT operations.

1.   Improve the latency of deployments performed by AWS CodeDeploy.

2.   Improve latency and throughput for read-heavy application workloads.

3.   Reduce the time required to merge AWS CodeCommit branchesImprove performance of compute-intensive applications.

4.   Improve performance of compute-intensive applications.


### Which of the following services are key/value stores? (Choose 3 answers)

<details>
<summary>Click to answer</summary>

- [x] Amazon ElastiCache.
- [x] DynamoDB.
- [x] Simple Storage Service.   

</details>

0.   Amazon ElastiCache.

1.   Simple Notification Service.

2.   DynamoDB.

3.   Simple Workflow Service.

4.   Simple Storage Service.


### A developer wants to send multi-value headers to an AWS Lambda function that is registered as a target with an Application Load Balancer (ALB). What should the developer do to achieve this?

<details>
<summary>Click to answer</summary>

- [x] Enable the multi-value headers on the ALB.   

</details>

0.   Place the Lambda function and target group in the same account.

1.   Send the request body to the Lambda function with a size less than 1 MB 0.

2.   Include the Base64 encoding status status code, status description, and headers in the Lambda function.

3.   Enable the multi-value headers on the ALB.


### A company's ecommerce website is experiencing massive traffic spikes, which are causing performance problems in the company database. Users are reporting that accessing the website takes a long time. A developer wants to implement a caching layer using Amazon ElastiCache. The website is required to be responsive no matter which product a user views, and the updates to product information and prices must be strongly consistent. Which cache writing policy will satisfy these requirements?

<details>
<summary>Click to answer</summary>

- [x] Write to the backend first and invalidate the cache.   

</details>

0.   Write to the cache directly and sync the backend at a later time.

1.   Write to the backend first and wait for the cache to expire.

2.   Write to the cache and the backend at the same time.

3.   Write to the backend first and invalidate the cache.


### A Developer wants to upload data to Amazon S3 and must encrypt the data in transit. Which of the following solutions will accomplish this task? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Set up Client-Side Encryption with an AWS KMS-Managed Customer Master Key.
- [x] Transfer the data over an SSL connectionSet up Server-Side Encryption with S3-Managed Keys.   

</details>

0.   Set up hardware VPN tunnels to a VPC and access S3 through a VPC endpoint.

1.   Set up Client-Side Encryption with an AWS KMS-Managed Customer Master Key.

2.   Set up Server-Side Encryption with AWS KMS-Managed Keys.

3.   Transfer the data over an SSL connectionSet up Server-Side Encryption with S3-Managed Keys.

4.   Set up Server-Side Encryption with S3-Managed Keys.


### A Developer wants to encrypt new objects that are being uploaded to an Amazon S3 bucket by an application. There must be an audit trail of who has used the key during this process. There should be no change to the performance of the application. Which type of encryption meets these requirements?

<details>
<summary>Click to answer</summary>

- [x] Server-side encryption with AWS KMS-managed keys.   

</details>

0.   Server-side encryption using S3-managed keys.

1.   Server-side encryption with AWS KMS-managed keys.

2.   Client-side encryption with a client-side symmetric master key.

3.   Client-side encryption with AWS KMS-managed keys.


### An application is being developed to audit several AWS accounts. The application will run in Account A and must access AWS services in Accounts B and C. What is the MOST secure way to allow the application to call AWS services in each audited account?

<details>
<summary>Click to answer</summary>

- [x] Configure cross-account roles in each audited account. Write code in Account A that assumes those roles.   

</details>

0.   Configure cross-account roles in each audited account. Write code in Account A that assumes those roles.

1.   Use S3 cross-region replication to communicate among accounts, with Amazon S3 event notifications to trigger Lambda functions.

2.   Deploy an application in each audited account with its own role. Have Account A authenticate with the application.

3.   Create an IAM user with an access key in each audited account. Write code in Account A that uses those access keys.


### A company uses a third-party tool to build, bundle, and package rts applications on-premises and store them locally. The company uses Amazon EC2 instances to run its front-end applications. How can an application be deployed from the source control system onto the EC2 instances?

<details>
<summary>Click to answer</summary>

- [x] Upload the bundle to an Amazon S3 bucket and specify the S3 location when doing a deployment using AWS CodeDeploy.   

</details>

0.   Use AWS CodeDeploy and point it to the local storage to directly deploy a bundle m a zip. tar. or tar.gz format.

1.   Upload the bundle to an Amazon S3 bucket and specify the S3 location when doing a deployment using AWS CodeDeploy.

2.   Create a repository using AWS CodeCommit to automatically trigger a deployment to the EC2 instances.

3.   Use AWS CodeBuild to automatically deploy the latest build to the latest EC2 instances.


### A company is building a compute-intensive application that will run on a fleet of Amazon EC2 instances. The application uses attached Amazon EBS disks for storing data. The application will process sensitive information and all the data must be encrypted. What should a developer do to ensure the data is encrypted on disk without impacting performance?

<details>
<summary>Click to answer</summary>

- [x] Configure the Amazon EC2 instance fleet to use encrypted EBS volumes for storing data.   

</details>

0.   Configure the Amazon EC2 instance fleet to use encrypted EBS volumes for storing data.

1.   Add logic to write all data to an encrypted Amazon S3 bucket.

2.   Add a custom encryption algorithm to the application that will encrypt and decrypt all data.

3.   Create a new Amazon Machine Image (AMI) with an encrypted root volume and store the data to ephemeral disks.


### A global company has an application running on Amazon EC2 instances that serves image files from Amazon S3. User requests from the browser are causing high traffic, which results in degraded performance. Which optimization solution should a Developer implement to increase application performance?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon CloudFront to serve the content of images stored in Amazon S3.   

</details>

0.   Create multiple prefix in the S3 bucket to increase the request rate.

1.   Create an Amazon ElastiCache cluster to cache and serve frequently accessed items.

2.   Use Amazon CloudFront to serve the content of images stored in Amazon S3.

3.   Submit a ticket to AWS support to request a rate limit increase for the S3 bucket.


### An AWS Lambda function generates a 3MB JSON file and then uploads it to an Amazon S3 bucket daily. The file contains sensitive information, so the Developer must ensure that it is encrypted before uploading to the bucket. Which of the following modifications should the Developer make to ensure that the data is encrypted before uploading it to the bucket?

<details>
<summary>Click to answer</summary>

- [x] Use the GenerateDateKey API, then use that data key to encrypt the file in the Lambda function code.   

</details>

0.   Use the default AWS KMS customer master key for S3 in the Lambda function code.

1.   Use the S3 managed key and call the GenerateDataKey API to encrypt the file.

2.   Use the GenerateDateKey API, then use that data key to encrypt the file in the Lambda function code.

3.   Use a custom KMS customer master key created for S3 in the Lambda function code.


### Company D is running their corporate website on Amazon S3 accessed from http://www.companyd.com. Their marketing team has published new web fonts to a separate S3 bucket accessed by the S3 endpoint https://s3-us-west-1.amazonaws.com/cdfonts. While testing the new web fonts, Company D recognized the web fonts are being blocked by the browser. What should Company D do to prevent the web fonts from being blocked by the browser?

<details>
<summary>Click to answer</summary>

- [x] Configure the cdfonts bucket to allow cross-origin requests by creating a CORS configuration.   

</details>

0.   Enable versioning on the cdfonts bucket for each web font.

1.   Create a policy on the cdfonts bucket to enable access to everyone.

2.   Add the Content-MD5 header to the request for webfonts in the cdfonts bucket from the website.

3.   Configure the cdfonts bucket to allow cross-origin requests by creating a CORS configuration.


### A developer must extend an existing application that is based on the AWS Services Application Model (AWS SAM). The developer has used the AWS SAM CLI to create the project. The project contains different AWS Lambda functions. Which combination of commands must the developer use to redeploy the AWS SAM application? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Sam init.
- [x] Sam deploySam publish.   

</details>

0.   Sam init.

1.   Sam validate.

2.   Sam build.

3.   Sam deploySam publish.

4.   Sam publish.


### An application deployed on AWS Elastic Beanstalk experiences increased error rates during deployments of new application versions, resulting in service degradation for users. The Development team believes that this is because of the reduction in capacity during the deployment steps. The team would like to change the deployment policy configuration of the environment to an option that maintains full capacity during deployment while using the existing instances. Which deployment policy will meet these requirements while using the existing instances?

<details>
<summary>Click to answer</summary>

- [x] Immutable.   

</details>

0.   All at once.

1.   Rolling.

2.   Rolling with additional batch.

3.   Immutable.


### A Developer is creating an application that needs to locate the public IPv4 address of the Amazon EC2 instance on which it runs . How can the application locate this information?

<details>
<summary>Click to answer</summary>

- [x] Get the instance metadata by retrieving http://169.254.169.254/latest/metadata/.   

</details>

0.   Get the instance metadata by retrieving http://169.254.169.254/latest/metadata/.

1.   Get the instance user data by retrieving http://169.254.169.254/latest/userdata/.

2.   Get the application to run IFCONFIG to get the public IP address.

3.   Get the application to run IPCONFIG to get the public IP address.


### The development team is working on an API that will be served from Amazon API gateway. The API will be served from three environments: development, test, and production. The API Gateway is configured to use 237 GB of cache in all three stages. Which is the MOST cost-efficient deployment strategy?

<details>
<summary>Click to answer</summary>

- [x] Enable the cache for development and test environments only when needed.   

</details>

0.   Create a single API Gateway with all three stages.

1.   Create three API Gateways, one for each stage in a single AWS account.

2.   Create an API Gateway in three separate AWS accounts.

3.   Enable the cache for development and test environments only when needed.


### A company is migrating its on-premises database to Amazon RDS for MySQL. The company has read-heavy workloads, and wants to make sure it re-factors its code to achieve optimum read performance for its queries. How can this objective be met?

<details>
<summary>Click to answer</summary>

- [x] Add a connection string to use an RDS read replica for read queries.   

</details>

0.   Add database retries to effectively use RDS with vertical scaling.

1.   Use RDS with multi-AZ deployment.

2.   Add a connection string to use an RDS read replica for read queries.

3.   Add a connection string to use a read replica on an EC2 instance.


### A developer needs to modify an application architecture to meet new functional requirements. Application data is stored in Amazon DynamoDB and processed for analysis in a rightly batch. The system analysts do not want to wait unit the next day to view the processed data and have asked to have it available in near-real time. Which application architect pattern would enables the data to be processed as it is received?

<details>
<summary>Click to answer</summary>

- [x] Evert driven.   

</details>

0.   Evert driven.

1.   Client served driven.

2.   Fan-out driven.

3.   Schedule driven.


### You are developing an HTTP API hosted on a Compute Engine virtual machine instance that needs to be invoked by multiple clients within the same Virtual Private Cloud (VPC). You want clients to be able to get the IP address of the service. What should you do?

<details>
<summary>Click to answer</summary>

- [x] Ensure that clients use Compute Engine internal DNS by connecting to the instance name with the url https://[INSTANCE_NAME].[ZONE].c.[PROJECT_ID].internal/.Ensure that clients use Compute Engine internal DNS by connecting to the instance name with the url https://[API_NAME]/[API_VERSION]/.   

</details>

0.   Reserve a static external IP address and assign it to an HTTP(S) load balancing service's forwarding rule. Clients should use this IP address to connect to the service.

1.   Reserve a static external IP address and assign it to an HTTP(S) load balancing service's forwarding rule. Then, define an A record in Cloud DNS.

2.   Clients should use the name of the A record to connect to the service.

3.   Ensure that clients use Compute Engine internal DNS by connecting to the instance name with the url https://[INSTANCE_NAME].[ZONE].c.[PROJECT_ID].internal/.Ensure that clients use Compute Engine internal DNS by connecting to the instance name with the url https://[API_NAME]/[API_VERSION]/.

4.   Ensure that clients use Compute Engine internal DNS by connecting to the instance name with the url https://[API_NAME]/[API_VERSION]/.


### A software company needs to make sure user-uploaded documents are securely stored in Amazon S3. The documents must be encrypted at rest in Amazon S3. The company does not want to manage the security infrastructure in-house, but the company still needs extra protection to ensure it has control over its encryption keys due to industry regulations. Which encryption strategy should a developer use to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Server-side encryption with customer-provided encryption keys (SSE-C).   

</details>

0.   Server-side encryption with Amazon S3 managed keys (SSE-S3).

1.   Server-side encryption with customer-provided encryption keys (SSE-C).

2.   Server-side encryption with AWS KMS managed keys (SSE-KMS).

3.   Client-side encryption.


### An application uses Amazon Kinesis Data Streams to ingest and process large streams of data records in real time. Amazon EC2 instances consume and process the data from the shards of the Kinesis data stream by using Amazon Kinesis Client Library (KCL). The application handles the failure scenarios and does not require standby workers. The application reports that a specific shard is receiving more data than expected. To adapt to the changes in the rate of data flow, the 'hot' shard is resharded. Assuming that the initial number of shards in the Kinesis data stream is 4, and after resharding the number of shards increased to 6, what is the maximum number of EC2 instances that can be deployed to process data from all the shards?

<details>
<summary>Click to answer</summary>

- [x] 6.   

</details>

0.   12.

1.   6.

2.   4.

3.   1.


### A gaming company is developing a mobile game application for iOS® and Android® platforms. This mobile game securely stores user data locally on the device. The company wants to allow users to use multiple device for the game, which requires user data synchronization across device.Which service should be used to synchronize user data across devices without the need to create a backend application?

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito.   

</details>

0.   AWS Lambda.

1.   Amazon S3.

2.   Amazon DynamoDB.

3.   Amazon Cognito.


### A Developer is making changes to a custom application that is currently using AWS Elastic Beanstalk. After the Developer completes the changes, what solutions will update the Elastic Beanstalk environment with the new application version? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Package the application code into a .tar file, and upload and deploy the packaged application from the AWS Management Console.
- [x] Package the application code into a .zip file, create a new application version from the packaged application by using AWS CLI, then update the environment by using AWS CLIPackage the application code into a .zip file, create a new application version from the AWS Management Console, then rebuild the environment by using AWS CLI.   

</details>

0.   Package the application code into a .zip file, and upload, then deploy the packaged application from the AWS Management Console.

1.   Package the application code into a .tar file, create a new application version from the AWS Management Console, then update the environment by using AWS CLI.

2.   Package the application code into a .tar file, and upload and deploy the packaged application from the AWS Management Console.

3.   Package the application code into a .zip file, create a new application version from the packaged application by using AWS CLI, then update the environment by using AWS CLIPackage the application code into a .zip file, create a new application version from the AWS Management Console, then rebuild the environment by using AWS CLI.

4.   Package the application code into a .zip file, create a new application version from the AWS Management Console, then rebuild the environment by using AWS CLI.


### A company is running an application built on AWS Lambda functions. One Lambda function has performance issues when it has to download a 50MB file from the Internet in every execution. This function is called multiple times a second. What solution would give the BEST performance increase?

<details>
<summary>Click to answer</summary>

- [x] Cache the file in the /tmp directory.   

</details>

0.   Cache the file in the /tmp directory.

1.   Increase the Lambda maximum execution time.

2.   Put an Elastic Load Balancer in front of the Lambda function.

3.   Cache the file in Amazon S3.


### Queries to an Amazon DynamoDB table are consuming a large amount of read capacity. The table has a significant number of large attributes. The application does not need all of the attribute data. How can DynamoDB costs be minimized while maximizing application performance?

<details>
<summary>Click to answer</summary>

- [x] Implement exponential backoffs in the application.   

</details>

0.   Batch all the writes, and perform the write operations when no or few reads are being performed.

1.   Create a global secondary index with a minimum set of projected attributes.

2.   Implement exponential backoffs in the application.

3.   Load balance the reads to the table using an Application Load Balancer.


### A Developer is writing a REST service that will add items to a shopping list. The service is built on Amazon API Gateway with AWS Lambda integrations. The shopping list items are send as query string parameters in the method request. How should the Developer convert the query string parameters to arguments for the Lambda function?

<details>
<summary>Click to answer</summary>

- [x] Create a mapping template.   

</details>

0.   Enable request validation.

1.   Include the Amazon Resource Name (ARN) of the Lambda function.

2.   Change the integration type.

3.   Create a mapping template.


### A development team is creating a new application designed to run on AWS. While the test and production environments will run on Amazon EC2 instances, developers will each run their own environment on their laptops. Which of the following is the simplest and MOST secure way to access AWS services from the local development machines?

<details>
<summary>Click to answer</summary>

- [x] Use an IAM role to assume a role and execute API calls using the role.   

</details>

0.   Use an IAM role to assume a role and execute API calls using the role.

1.   Create an IAM user to be shared with the entire development team, provide the development team with the access key.

2.   Create an IAM user for each developer on the team: provide each developer with a unique access key.

3.   Set up a federation through an Amazon Cognito user pool.


### How is provisioned throughput affected by the chosen consistency model when reading data from a DynamoDB table?

<details>
<summary>Click to answer</summary>

- [x] Strongly consistent reads use more throughput than eventually consistent reads.   

</details>

0.   Strongly consistent reads use the same amount of throughput as eventually consistent reads.

1.   Strongly consistent reads use more throughput than eventually consistent reads.

2.   Strongly consistent reads use less throughput than eventually consistent reads.

3.   Strongly consistent reads use variable throughput depending on read activity.


### A developer needs to deploy a new version to an AWS Elastic Beanstalk application. How can the developer accomplish this task?

<details>
<summary>Click to answer</summary>

- [x] Upload and deploy the new application version in the Elastic Beanstalk console.   

</details>

0.   Upload and deploy the new application version in the Elastic Beanstalk console.

1.   Use the eb init CLI command to deploy a new version.

2.   Terminate the current Elastic Beanstalk environment and create a new one.

3.   Modify the ebextensions folder to add a source option to services.


### A gaming application stores scores for players in an Amazon DynamoDB table that has four attributes: user_id, user_name, user_score, and user_rank. The users are allowed to update their names only A user is authenticated by web identity federation. Which set of conditions should be added in the policy attached to the role for the DynamoDB: PutItem API call?

<details>
<summary>Click to answer</summary>

- [x] Option A.   

</details>

0.   Option A.

1.   Option B.

2.   Option C.

3.   Option D.


### A developer wants the ability to roll back to a previous version of an AWS Lambda function in the event of errors caused by a new deployment. How can the developer achieve this with MINIMAL impact on users?

<details>
<summary>Click to answer</summary>

- [x] Change the application to use an alias that points to the current version Deploy the new version of the code Update the alias to use the newly deployed version. If too many errors are encountered, point the alias back to the previous version.   

</details>

0.   Change the application to use an alias that points to the current version Deploy the new version of the code Update the alias to use the newly deployed version. If too many errors are encountered, point the alias back to the previous version.

1.   Change the application to use an alias that points to the current version Deploy the new version of the code. Update the alias to direct 10% of users to the newly deployed version. If too many errors are encountered, send 100% of traffic to the previous version.

2.   Do not make any changes to the application Deploy the new version of the code. If too many errors are encountered, point the application back to the previous version using the version number in the Amazon Resource Name (ARN).

3.   Create three aliases: new, existing, and router Point the existing alias to the current version Have the router alias direct 100% of users to the existing alias Update the application to use the router alias Deploy the new version of the code Point the new alias to this version Update the router alias to direct 10% of users to the new alias If too many errors are encountered, send 100% of traffic to the existing alias.


### An application contains two components one component to handle HI IP requests, and another component to handle background processing tasks Bach component must scale independently. The developer wants to deploy this application using AWS Elastic Beanstalk. How should this application be deployed, based on these requirements?

<details>
<summary>Click to answer</summary>

- [x] Deploy the application in a single Elastic Beanstalk environment.   

</details>

0.   Deploy the application in a single Elastic Beanstalk environment.

1.   Deploy each component in a separate Elastic Beanstalk environment.

2.   Use multiple Elastic Beanstalk environments for the HTTP component but one environment for the background task component.

3.   Use multiple Elastic Beanstalk environments for the background task component but one environment tor the HTTP component.


### A company is using AWS CloudFormation templates to deploy AWS resources. The company needs to update one of its AWS CloudFormation stacks. What can the company do to find out how the changes will impact the resources that are running?

<details>
<summary>Click to answer</summary>

- [x] Investigate the change sets.   

</details>

0.   Investigate the change sets.

1.   Investigate the stack policies.

2.   Investigate the Metadata section.

3.   Investigate the Resources section.


### A developer is creating a serverless web application and maintains different branches of code. The developer wants to avoid updating the Amazon API Gateway target endpoint each time a new code push is performed. What solution would allow me developer toPerform a code push efficiently, without the need to update the API Gateway?

<details>
<summary>Click to answer</summary>

- [x] Create different stages in API Gateway, then associate API Gateway with aws Lambda.   

</details>

0.   Associate different AWS Lambda functions to an API Gateway target endpoint.

1.   Create different stages in API Gateway, then associate API Gateway with aws Lambda.

2.   Create aliases and versions In AWS Lambda.

3.   Tag the AWS Lambda functions with different names.


### An application running on EC2 instances is storing data in an S3 bucket. Security policy mandates that all data must be encrypted in transit. How can the Developer ensure that all traffic to the S3 bucket is encrypted?

<details>
<summary>Click to answer</summary>

- [x] Create a bucket policy that denies traffic where SecureTransport is false.   

</details>

0.   Install certificates on the EC2 instances.

1.   Create a bucket policy that allows traffic where SecureTransport is true.

2.   Create an HTTPS redirect on the EC2 instances.

3.   Create a bucket policy that denies traffic where SecureTransport is false.


### A supplier is writing a new RESTful API for customers to query the status of orders. The customers requested the following API endpoint http://www.supplierdomain.com/status/customerID. Which of the following application designs meet the requirements? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Amazon API Gateway; AWS LambdaAmazon S3; Amazon CloudFront.
- [x] Amazon S3; Amazon CloudFront.   

</details>

0.   Amazon SQS; Amazon SNS.

1.   Elastic Load Balancing; Amazon EC2.

2.   Amazon ElastiCache; Amazon Elacticsearch Service.

3.   Amazon API Gateway; AWS LambdaAmazon S3; Amazon CloudFront.

4.   Amazon S3; Amazon CloudFront.


### A developer Is designing an AWS Lambda function that create temporary files that are less than 10 MB during execution. The temporary files will be accessed and modified multiple times during execution. The developer has no need to save or retrieve these files in the future. Where should the temporary file be stored?

<details>
<summary>Click to answer</summary>

- [x] the /tmp directory.   

</details>

0.   the /tmp directory.

1.   Amazon EFS.

2.   Amazon EBS.

3.   Amazon S3.


### A website's page load times are gradually increasing as more users access the system at the same time. Analysis indicates that a user profile is being loaded from a database in all the web pages being visited by each user and this is increasing the database load and the page load latency. To address this issue the Developer decides to cache the user profile data. Which caching strategy will address this situation MOST efficiently?

<details>
<summary>Click to answer</summary>

- [x] Create an Amazon ElastiCache cluster to cache the user profile data. Use a cache-aside caching strategy.   

</details>

0.   Create a new Amazon EC2 Instance and run a NoSQL database on it. Cache the profile data within this database using the write-through caching strategy.

1.   Create an Amazon ElastiCache cluster to cache the user profile data. Use a cache-aside caching strategy.

2.   Use a dedicated Amazon RDS instance for caching profile data. Use a write-through caching strategy.

3.   Create an ElastiCache cluster to cache the user profile data. Use a write-through caching strategy.


### An advertising company has a dynamic website with heavy traffic. The company wants to migrate the website infrastructure to AWS to handle everything except website development. Which solution BEST meets these requirements?

<details>
<summary>Click to answer</summary>

- [x] Deploy the website code in an AWS Elastic Beanstalk environment. Use Auto Scaling to scale the numbers of instance.   

</details>

0.   Use AWS VM Import to migrate a web server image to AWS Launch the image on a compute-optimized Amazon EC2 instanceLaunch.

1.   Launch multiple Amazon Lighsall instance behind a load balancer. Set up the website on those instances.

2.   Deploy the website code in an AWS Elastic Beanstalk environment. Use Auto Scaling to scale the numbers of instance.

3.   Use Amazon S3 to host the website. Use Amazon CloudFornt to deliver the content at scale.


### A developer is writing an AWS Lambda function. The developer wants to log key events that occur during the Lambda function and include a unique identifier to associate the events with a specific function invocation. Which of the following will help the developer accomplish this objective?

<details>
<summary>Click to answer</summary>

- [x] Obtain the request identifier from the Lambda context object Architect the application to write logs to the console.   

</details>

0.   Obtain the request identifier from the Lambda context object Architect the application to write logs to the console.

1.   Obtain the request identifier from the Lambda event object Architect the application to write logs to a file.

2.   Obtain the request identifier from the Lambda event object Architect the application to write logs to the console.

3.   Obtain the request identifier from the Lambda context object Architect the application to write logs to a file.


### A company stores all personally identifiable information (PII) in an Amazon DynamoDB table named PII in Account A. An application running on Amazon EC2 instances in Account B requires access to the PII table. An administrators in Account A created an IAM role named AccessPII with privileges to access the PII table, and made account B a trusted entity. Which combination of actional steps should Developers take to access the table? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Ask an Administrator in Account B to allow the EC2 IAM role permission to assume the AccessPII role with predefined service control policies.
- [x] Include the AssumeRole API in the application code logic to obtain credentials to access the PII table.   

</details>

0.   Ask an Administrator in Account B to allow the EC2 IAM role permission to assume the AccessPII role.

1.   Ask an Administrator in Account B to allow the EC2 IAM role permission to assume the AccessPII role with predefined service control policies.

2.   Ask an Administrator in Account A to allow the EG2 IAM role permission to assume the AccessPII role with predefined service control policies.

3.   Include the AssumeRole API in the application code logic to obtain credentials to access the PII table.

4.   Include the GetSession token API in the application code logic to obtain credentials to access the PII table.


### An AWS Lambda function accesses two Amazon DynamoDB tables. A developer wants to improve the performance of the Lambda function by identifying bottlenecks in the function. How can the developer inspect the timing of the DynamoDB API calls?

<details>
<summary>Click to answer</summary>

- [x] Add DynamoDB as an event source to the Lambda function. View the performance with Amazon CloudWatch metrics.   

</details>

0.   Add DynamoDB as an event source to the Lambda function. View the performance with Amazon CloudWatch metrics.

1.   Place an Application Load Balancer (ALB) in front of the two DynamoDB tables. Inspect the ALB logs.

2.   Limit Lambda to no more than five concurrent invocations Monitor from the Lambda console.

3.   Enable AWS X-Ray tracing for the function. View the traces from the X-Ray service.


### An Amazon RDS database instance is used by many applications to look up historical data. The query rate is relatively constant. When the historical data is updated each day, the resulting write traffic slows the read query performance and affects all application users. What can be done to eliminate the performance impact on application users?

<details>
<summary>Click to answer</summary>

- [x] Create an RDS Read Replica and direct all read traffic to the replica.   

</details>

0.   Make sure Amazon RDS is Multi-AZ so it can better absorb increased traffic.

1.   Create an RDS Read Replica and direct all read traffic to the replica.

2.   Implement Amazon ElastiCache in front of Amazon RDS to buffer the write traffic.

3.   Use Amazon DynamoDB instead of Amazon RDS to buffer the read traffic.


### A company is developing a serverless ecommerce web application. The application needs to make coordinated, all-or-nothing changes to multiple items in the company's inventory table in Amazon DynamoDB. Which solution will meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Use the Transact Writeitem operation to group the changes Update the items in the table.   

</details>

0.   Enable transactions for the DynamoDB table Use the Batch Writeltem operation to update the items.

1.   Use the Transact Writeitem operation to group the changes Update the items in the table.

2.   Set up a FIFO queue using Amazon SQ.

3.   Group the changes in the queue. Update the table based on the grouped changesCreate a transaction table in an Amazon Aurora DB cluster to manage the transactions Write a backend process to sync the Aurora DB table and the DynamoDB table.

4.   Create a transaction table in an Amazon Aurora DB cluster to manage the transactions Write a backend process to sync the Aurora DB table and the DynamoDB table.


### An application is running on an EC2 instance. The Developer wants to store an application metric in Amazon CloudWatch. What is the best practice for implementing this requirement?

<details>
<summary>Click to answer</summary>

- [x] Use the CloudWatch PutMetricData API call to submit a custom metric to CloudWatch. Launch the EC2 instance with the required IAM role to enable the API call.   

</details>

0.   Use the PUT Object API call to send data to an S3 bucket. Use an event notification to invoke a Lambda function to publish data to CloudWatch.

1.   Publish the metric data to an Amazon Kinesis Stream using a PutRecord API call. Subscribe a Lambda function that publishes data to CloudWatch.

2.   Use the CloudWatch PutMetricData API call to submit a custom metric to CloudWatch. Provide the required credentials to enable the API call.

3.   Use the CloudWatch PutMetricData API call to submit a custom metric to CloudWatch. Launch the EC2 instance with the required IAM role to enable the API call.


### A Developer needs to design an application running on AWS that will be used to consume Amazon SQS messages that range from 1 KB up to 1GB in size. How should the Amazon SQS messages be managed?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon S3 and the Amazon SQS Extended Client Library for Java.   

</details>

0.   Use Amazon S3 and the Amazon SQS CLI.

1.   Use Amazon S3 and the Amazon SQS Extended Client Library for Java.

2.   Use Amazon EBS and the Amazon SQS CLI.

3.   Use Amazon EFS and the Amazon SQS CLI.


### A developer has written a multi-threaded application that is running on a fleet of Amazon EC2 instances. The operations team has requested a graphical method to monitor the number of running threads over time. What is the MOST efficient way to fulfill this request?

<details>
<summary>Click to answer</summary>

- [x] Periodically write the current thread count to a table using Amazon DynarnoDB and use Amazon CloudFront to create a graph.   

</details>

0.   Periodically send the thread count to AWS X-Ray segments, then generate a service graph on demand.

1.   Create a custom Amazon CloudWatch metric and periodically perform a PutMetricData call with the current thread count.

2.   Periodically log thread count data to Amazon S3. Use Amazon Kinesis to process the data into a graph.

3.   Periodically write the current thread count to a table using Amazon DynarnoDB and use Amazon CloudFront to create a graph.


### The Lambda function below is being called through an API using Amazon API Gateway. The average execution time for the Lambda function is about 1 second. The pseudocode for the Lambda function is as shown in the exhibit. What two actions can be taken to improve the performance of this Lambda function without increasing the cost of the solution? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Package only the modules the Lambda function requires.
- [x] Implement local caching of Amazon RDS data so Lambda can re-use the cache.   

</details>

0.   Package only the modules the Lambda function requires.

1.   Use Amazon DynamoDB instead of Amazon RDS.

2.   Move the initialization of the variable Amazon RDS connection outside of the handler function.

3.   Implement custom database connection pooling with the Lambda function.

4.   Implement local caching of Amazon RDS data so Lambda can re-use the cache.


### An application on AWS is using third-party APIs. The Developer needs to monitor API errors in the code, and wants to receive notifications if failures go above a set threshold value. How can the Developer achieve these requirements?

<details>
<summary>Click to answer</summary>

- [x] Publish a custom metric on Amazon CloudWatch and use Amazon SNS for notification.   

</details>

0.   Publish a custom metric on Amazon CloudWatch and use Amazon SES for notification.

1.   Use an Amazon CloudWatch API-error metric and use Amazon SNS for notification.

2.   Use an Amazon CloudWatch API-error metric and use Amazon SES for notification.

3.   Publish a custom metric on Amazon CloudWatch and use Amazon SNS for notification.


### The release process workflow of an application requires a manual approval before the code is deployed into the production environment. What is the BEST way to achieve this using AWS CodePipeline?

<details>
<summary>Click to answer</summary>

- [x] Use an approval action in a stage.   

</details>

0.   Use multiple pipelines to allow approval.

1.   Use an approval action in a stage.

2.   Disable the stage transition to allow manual approval.

3.   Disable a stage just prior the deployment stage.


### A Developer is asked to implement a caching layer in front of Amazon RDS. Cached content is expensive to regenerate in case of service failure. Which implementation below would work while maintaining maximum uptime?

<details>
<summary>Click to answer</summary>

- [x] Implement Amazon ElastiCache Redis in Cluster Mode.   

</details>

0.   Implement Amazon ElastiCache Redis in Cluster Mode.

1.   Install Redis on an Amazon EC2 instance.

2.   Implement Amazon ElastiCache Memcached.

3.   Migrate the database to Amazon Redshift.


### A company has written a Java AWS Lambda function to be triggered whenever a user uploads an image to an Amazon S3 bucket. The function converts the original image to several different formats and then copies the resulting images to another Amazon S3 bucket. The Developers find that no images are being copied to the second Amazon S3 bucket. They have tested the code on an Amazon EC2 instance with 1GB of RAM, and it takes an average of 500 seconds to complete. What is the MOST likely cause of the problem?

<details>
<summary>Click to answer</summary>

- [x] Lambda functions have a maximum execution limit of 300 seconds, therefore the function is not completing.   

</details>

0.   The Lambda function has insufficient memory and needs to be increased to 1 GB to match the Amazon EC2 instance.

1.   Files need to be copied to the same Amazon S3 bucket for processing, so the second bucket needs to be deleted.

2.   Lambda functions have a maximum execution limit of 300 seconds, therefore the function is not completing.

3.   There is a problem with the Java runtime for Lambda, and the function needs to be converted to node.js.


### A web application is using Amazon Kinesis Streams for clickstream data that may not be consumed for up to 12 hours. How can the Developer implement encryption at rest for data within the Kinesis Streams?

<details>
<summary>Click to answer</summary>

- [x] Enable server-side encryption in Kinesis Streams.   

</details>

0.   Enable SSL connections to Kinesis.

1.   Use Amazon Kinesis Consumer Library.

2.   Encrypt the data once it is at rest with a Lambda function.

3.   Enable server-side encryption in Kinesis Streams.


### A Developer is creating a mobile application with a limited budget. The solution requires a scalable service that will enable customers to sign up and authenticate into the mobile application while using the organization's current SAML 2.0 identity provider. Which AWS service should be used to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito.   

</details>

0.   AWS Lambda.

1.   Amazon Cognito.

2.   AWS IAM.

3.   Amazon EC2.


### A company wants to migrate its web application to AWS and leverage Auto Scaling to handle pear workloads. The Solutions Architect determined that the best metric for an Auto Scaling event is the number of concurrent users. Based on this information, what should the Developer use to autoscale based on concurrent users?

<details>
<summary>Click to answer</summary>

- [x] A Custom Amazon CloudWatch metric for concurrent users.   

</details>

0.   An Amazon SNS topic to be triggered when a concurrent user threshold is met.

1.   An Amazon Cloudwatch Networkin metric.

2.   Amazon CloudFront to leverage AWS Edge Locations.

3.   A Custom Amazon CloudWatch metric for concurrent users.


### A Developer has written a serverless application using multiple AWS services. The business logic is written as a Lambda function which has dependencies on third-party libraries. The Lambda function endpoints will be exposed using Amazon API Gateway. The Lambda function will write the information to Amazon DynamoDB. The Developer is ready to deploy the application but must have the ability to rollback. How can this deployment be automated, based on these requirements?

<details>
<summary>Click to answer</summary>

- [x] Deploy using Amazon Lambda API operations to create the Lambda function by providing a deployment package.   

</details>

0.   Deploy using Amazon Lambda API operations to create the Lambda function by providing a deployment package.

1.   Use an AWS CloudFormation template and use CloudFormation syntax to define the Lambda function resource in the template.

2.   Use syntax conforming to the Serverless Application Model in the AWS CloudFormation template to define the Lambda function resource.

3.   Create a bash script which uses AWS CLI to package and deploy the application.


### A game stores user game data in an Amazon DynamoDB table. Individual users should not have access to other users' game data. How can this be accomplished?

<details>
<summary>Click to answer</summary>

- [x] Restrict access to specific items based on certain primary key values.   

</details>

0.   Encrypt the game data with individual user keys.

1.   Restrict access to specific items based on certain primary key values.

2.   Stage data in SQS queues to inject metadata before accessing DynamoD.

3.   Read records from DynamoDB and discard irrelevant data client-side.


### A Developer is creating a web application that requires authentication, but also needs to support guest access to provide users limited access without having to authenticate. What service can provide support for the application to allow guest access?

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito with unauthenticated access enabled.   

</details>

0.   IAM temporary credentials using AWS STS.

1.   Amazon Directory Service.

2.   Amazon Cognito with unauthenticated access enabled.

3.   IAM with SAML integration


### Given the source code for an AWS Lambda function in the local store.py containing a handler function called get_store and the following AWS CloudFormation template: What should be done to prepare the template so that it can be deployed using the AWS CLI command aws cloudformation deploy?

<details>
<summary>Click to answer</summary>

- [x] Use aws serverless create-package to embed the source file directly into the existing CloudFormation template.   

</details>

0.   Use aws cloudformation compile to base64 encode and embed the source file into a modified CloudFormation template.

1.   Use aws cloudformation package to upload the source code to an Amazon S3 bucket and produce a modified CloudFormation template.

2.   Use aws lambda zip to package the source file together with the CloudFormation template and deploy the resulting zip archive.

3.   Use aws serverless create-package to embed the source file directly into the existing CloudFormation template.


### A Developer has created a large Lambda function, and deployment is failing with the following error:ClientError: An error occurred (InvalidParameterValueException) when calling the CreateFunction operation: Unzipped size must be smaller than XXXXXXXXX bytes', where XXXXXXXXX is the current Lambda limit. What can the Developer do to fix this problem?

<details>
<summary>Click to answer</summary>

- [x] Break the function into multiple smaller Lambda functions.   

</details>

0.   Submit a limit increase request to AWS Support to increase the function to the size needed.

1.   Use a compression algorithm that is more efficient than ZI.

2.   Break the function into multiple smaller Lambda functions.

3.   ZIP the ZIP file twice to compress it further.


### A serverless application uses an API Gateway and AWS Lambda. Where should the Lambda function store its session information across function calls?

<details>
<summary>Click to answer</summary>

- [x] In an Amazon DynamoDB table.   

</details>

0.   In an Amazon DynamoDB table.

1.   In an Amazon SQS queue.

2.   In the local filesystem.

3.   In an SQLite session table using CDSQLITE_ENABLE_SESSION.


### An application reads data from an Amazon DynamoDB table. Several times a day, for a period of 15 seconds, the application receives multiple ProvisionedThroughputExceeded errors. How should this exception be handled?

<details>
<summary>Click to answer</summary>

- [x] Retry the failed read requests with exponential backoff.   

</details>

0.   Create a new global secondary index for the table to help with the additional requests.

1.   Retry the failed read requests with exponential backoff.

2.   Immediately retry the failed read requests.

3.   Use the DynamoDB 'UpdateItem' API to increase the provisioned throughput capacity of the table.


### A Developer is writing a Linux-based application to run on AWS Elastic Beanstalk. Application requirements state that the application must maintain full capacity during updates while minimizing cost. Which type of Elastic Beanstalk deployment policy should the Developer specify for the environment?

<details>
<summary>Click to answer</summary>

- [x] Immutable.   

</details>

0.   Immutable.

1.   Rolling.

2.   All at Once.

3.   Rolling with additional batch.


### When writing a Lambda function, what is the benefit of instantiating AWS clients outside the scope of the handler?

<details>
<summary>Click to answer</summary>

- [x] Taking advantage of connection re-use.   

</details>

0.   Legibility and stylistic convention.

1.   Taking advantage of connection re-use.

2.   Better error handling.

3.   Creating a new instance per invocation.


### A current architecture uses many Lambda functions invoking one another as large state machine. The coordination of this state machine is legacy custom code that breaks easily. Which AWS Service can help refactor and manage the state machine?

<details>
<summary>Click to answer</summary>

- [x] AWS Step Functions.   

</details>

0.   AWS Data Pipeline.

1.   AWS SNS with AWS SQS.

2.   Amazon Elastic MapReduce.

3.   AWS Step Functions.


### A company is developing a new online game that will run on top of Amazon ECS. Four distinct Amazon ECS services will be part of the architecture, each requiring specific permissions to various AWS services. The company wants to optimize the use of the underlying Amazon EC2 instances by bin packing the containers based on memory reservation. Which configuration would allow the Development team to meet these requirements MOST securely?

<details>
<summary>Click to answer</summary>

- [x] Create four distinct IAM roles, each containing the required permissions for the associated ECS service, then, create an IAM group and configure the ECS cluster to reference that group.   

</details>

0.   Create a new Identity and Access Management (IAM) instance profile containing the required permissions for the various ECS services, then associate that instance role with the underlying EC2 instances.

1.   Create four distinct IAM roles, each containing the required permissions for the associated ECS service, then configure each ECS service to reference the associated IAM role.

2.   Create four distinct IAM roles, each containing the required permissions for the associated ECS service, then, create an IAM group and configure the ECS cluster to reference that group.

3.   Create four distinct IAM roles, each containing the required permissions for the associated ECS service, then configure each ECS task definition to referenсe the associated IAM role.


### A Developer must re-implement the business logic for an order fulfilment system. The business logic has to make requests to multiple vendors to decide where to purchase an item. The whole process can take up to a week to complete. What is the MOST efficient and SIMPLEST way to implement a system that meets these requirements?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon CloudWatch Events to orchestrate the Lambda functions.   

</details>

0.   Use AWS Step Functions to execute parallel Lambda functions, and join the results.

1.   Create an AWS SQS for each vendor, poll the queue from a worker instance, and joint the results.

2.   Use AWS Lambda to asynchronously call a Lambda function for each vendor, and join the results.

3.   Use Amazon CloudWatch Events to orchestrate the Lambda functions.


### What best practice should first be applied to address this issue?

<details>
<summary>Click to answer</summary>

- [x] Use the AWS CLI to get the metrics.   

</details>

0.   Contact AWS Support for a limit increase.

1.   Use the AWS CLI to get the metrics.

2.   Analyze the applications and remove the API call.

3.   Retry the call with exponential backoff.


### A Developer is receiving HTTP 400: ThrottlingException errors intermittently when calling the Amazon CloudWatch API. When a call fails, no data is retrieved. Which techniques will work? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Define a Swagger file. Deploy a SAM template that references the Swagger file.
- [x] Define an inline Swagger definition in a Lambda function. Invoke the Lambda function.   

</details>

0.   Define a Swagger file. Use AWS Elastic Beanstalk to deploy the Swagger file.

1.   Define a Swagger file. Use AWS CodeDeploy to deploy the Swagger file.

2.   Deploy a SAM template with an inline Swagger definition.

3.   Define a Swagger file. Deploy a SAM template that references the Swagger file.

4.   Define an inline Swagger definition in a Lambda function. Invoke the Lambda function.


### An application is real-time processing millions of events that are received through an API. What service could be used to allow multiple consumers to process the data concurrently and MOST cost-effectively?

<details>
<summary>Click to answer</summary>

- [x] Amazon Kinesis Streams.   

</details>

0.   Amazon SNS with fanout to an SQS queue for each application.

1.   Amazon SNS with fanout to an SQS FIFO (first-in, first-out) queue for each application.

2.   Amazon Kinesis Firehouse.

3.   Amazon Kinesis Streams.


### Where should the appspec.yml file be placed in order for AWS CodeDeploy to work?

<details>
<summary>Click to answer</summary>

- [x] In the root of the application source code directory structure.   

</details>

0.   In the root of the application source code directory structure.

1.   In the bin folder along with all the complied code.

2.   In an S3 bucket.

3.   In the same folder as the application configuration files.


### An application will ingest data at a very high throughput from many sources and must store the data in an Amazon S3 bucket. Which service would BEST accomplish this task?

<details>
<summary>Click to answer</summary>

- [x] Amazon Kinesis Firehose.   

</details>

0.   Amazon Kinesis Firehose.

1.   Amazon S3 Acceleration Transfer.

2.   Amazon SQS.

3.   Amazon SNS.


### A Developer is creating a Lambda function and will be using external libraries that are not included in the standard Lambda libraries. What action would minimize the Lambda compute time consumed?

<details>
<summary>Click to answer</summary>

- [x] Install the external libraries in Lambda to be available to all Lambda functions.   

</details>

0.   Install the dependencies and external libraries at the beginning of the Lambda function.

1.   Create a Lambda deployment package that includes the external libraries.

2.   Copy the external libraries to Amazon S3, and reference the external libraries to the S3 location.

3.   Install the external libraries in Lambda to be available to all Lambda functions.


### During non-peak hours, a Developer wants to minimize the execution time of a full Amazon DynamoDB table scan without affecting normal workloads. The workloads average half of the strongly consistent read capacity units during non-peak hours. How would the Developer optimize this scan?

<details>
<summary>Click to answer</summary>

- [x] Use sequential scans.   

</details>

0.   Use parallel scans while limiting the rate.

1.   Use sequential scans.

2.   Increase read capacity units during the scan operation.

3.   Change consistency to eventually consistent during the scan operation.


### A large e-commerce site is being designed to deliver static objects from Amazon S3. The Amazon S3 bucket will server more than 300 GET requests per second. What should be done to optimize performance? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Integrate Amazon CloudFront with Amazon S3.
- [x] Enable Amazon S3 cross-region replication.   

</details>

0.   Integrate Amazon CloudFront with Amazon S3.

1.   Enable Amazon S3 cross-region replication.

2.   Delete expired Amazon S3 server log files.

3.   Configure Amazon S3 lifecycle rules.Randomize Amazon S3 key name prefixes.

4.   Randomize Amazon S3 key name prefixes.


### A legacy service has an XML-based SOAP interface. The Developer wants to expose the functionality of the service to external clients with the Amazon API Gateway. Which technique will accomplish this?

<details>
<summary>Click to answer</summary>

- [x] Create a RESTful API with the API Gateway; transform the incoming JSON into a valid XML message for the SOAP interface using mapping templates.   

</details>

0.   Create a RESTful API with the API Gateway; transform the incoming JSON into a valid XML message for the SOAP interface using mapping templates.

1.   Create a RESTful API with the API Gateway; pass the incoming JSON to the SOAP interface through an Application Load Balancer.

2.   Create a RESTful API with the API Gateway; pass the incoming XML to the SOAP interface through an Application Load Balancer.

3.   Create a RESTful API with the API Gateway; transform the incoming XML into a valid message for the SOAP interface using mapping templates.


### A Developer has an application that can upload tens of thousands of objects per second to Amazon S3 in parallel within a single AWS account. As part of new requirements, data stored in S3 must use server side encryption with AWS KMS (SSE-KMS). After creating this change, performance of the application is slower. Which of the following is MOST likely the cause of the application latency?

<details>
<summary>Click to answer</summary>

- [x] The AWS KMS API calls limit is less than needed to achieve the desired performance.   

</details>

0.   Amazon S3 throttles the rate at which uploaded objects can be encrypted using Customer Master Keys.

1.   The AWS KMS API calls limit is less than needed to achieve the desired performance.

2.   The client encryption of the objects is using a poor algorithm.

3.   KMS requires that an alias be used to create an independent display name that can be mapped to a CM.


### A customer wants to deploy its source code on an AWS Elastic Beanstalk environment. The customer needs to perform deployment with minimal outage and should only use existing instances to retain application access log. What deployment policy would satisfy these requirements?

<details>
<summary>Click to answer</summary>

- [x] Rolling.   

</details>

0.   Rolling.

1.   All at once.

2.   Rolling with an additional batch.

3.   Immutable.


### A Developer has setup an Amazon Kinesis Stream with 4 shards to ingest a maximum of 2500 records per second. A Lambda function has been configured to process these records. In which order will these records be processed?

<details>
<summary>Click to answer</summary>

- [x] Lambda will receive each record in the exact order it was placed into the stream following a FIFO (first­-in, first-out) method.   

</details>

0.   Lambda will receive each record in the reverse order it was placed into the stream following a LIFO (last-in, first-out) method.

1.   Lambda will receive each record in the exact order it was placed into the stream following a FIFO (first­-in, first-out) method.

2.   Lambda will receive each record in the exact order it was placed into the stream following a FIFO (first­-in, first-out) method.

3.   The Developer can select FIFO, (first-in, first-out), LIFO (last-in, last-out), random, or request specific record using the getRecords AP.


### An organization must store thousands of sensitive audio and video files in an Amazon S3 bucket. Organizational security policies require that all data written to this bucket be encrypted. How can compliance with this policy be ensured?

<details>
<summary>Click to answer</summary>

- [x] Configure an Amazon S3 bucket policy to prevent the upload of objects that do not contain the x-amz­server-side-encryption header.   

</details>

0.   Use AWS Lambda to send notifications to the security team if unencrypted objects are pun in the bucket.

1.   Configure an Amazon S3 bucket policy to prevent the upload of objects that do not contain the x-amz­server-side-encryption header.

2.   Create an Amazon CloudWatch event rule to verify that all objects stored in the Amazon S3 bucket are encrypted.

3.   Configure an Amazon S3 bucket policy to prevent the upload of objects that contain the x-amz-server­side-encryption header.


### An application is designed to use Amazon SQS to manage messages from many independent senders. Each sender's messages must be processed in the order they are received. Which SQS feature should be implemented by the Developer?

<details>
<summary>Click to answer</summary>

- [x] Configure each message with unique MessageGroupIds.   

</details>

0.   Configure each sender with a unique MessageGroupId.

1.   Enable MessageDeduplicationIds on the SQS queue.

2.   Configure each message with unique MessageGroupIds.

3.   Enable ContentBasedDeduplication on the SQS queue.


### A Developer created a dashboard for an application using Amazon API Gateway, Amazon S3, AWS Lambda, and Amazon RDS. The Developer needs an authentication mechanism allowing a user to sign in and view the dashboard. It must be accessible from mobile applications, desktops, and tablets, and must remember user preferences across platforms. Which AWS service should the Developer use to support this authentication scenario?

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito.   

</details>

0.   AWS KMS.

1.   Amazon Cognito.

2.   AWS Directory Service.

3.   Amazon IAM.


### A Lambda function is packaged for deployment to multiple environments, including development, test, production, etc. Each environment has unique set of resources such as databases, etc. How can the Lambda function use the resources for the current environment?

<details>
<summary>Click to answer</summary>

- [x] Use environment variables for the Lambda functions.   

</details>

0.   Apply tags to the Lambda functions.

1.   Hardcore resources in the source code.

2.   Use environment variables for the Lambda functions.

3.   Use separate function for development and production.


### A Developer needs temporary access to resources in a second account. What is the MOST secure way to achieve this?

<details>
<summary>Click to answer</summary>

- [x] Create a cross-account access role, and use sts: AssumeRole API to get short-lived credentials.   

</details>

0.   Use the Amazon Cognito user pools to get short-lived credentials for the second account.

1.   Create a dedicated IAM access key for the second account, and send it by mail.

2.   Create a cross-account access role, and use sts: AssumeRole API to get short-lived credentials.

3.   Establish trust, and add an SSH key for the second account to the IAM user.


### A Developer needs to use AWS X-Ray to monitor an application that is deployed on EC2 instances. What steps have to be executed to perform the monitoring?

<details>
<summary>Click to answer</summary>

- [x] Deploy the X-Ray SDK with the application and use X-Ray annotation.   

</details>

0.   Deploy the X-Ray SDK with the application and use X-Ray annotation.

1.   Install the X-Ray daemon and instrument the application code.

2.   Install the X-Ray daemon and configure it to forward data to Amazon CloudWatch Events.

3.   Deploy the X-Ray SDK with the application and instrument the application code.


### A Developer is creating an Auto Scaling group whose instances need to publish a custom metric to Amazon CloudWatch. Which method would be the MOST secure way to authenticate a CloudWatch PUT request?

<details>
<summary>Click to answer</summary>

- [x] Create an IAM role with PutMetricData permission and modify the Auto Scaling launching configuration to launch instances using that role.   

</details>

0.   Create an IAM user with PutMetricData permission and put the user credentials in a private repository; have applications pull the credentials as needed.

1.   Create an IAM user with PutMetricData permission, and modify the Auto Scaling launch configuration to inject the user credentials into the instance user data.

2.   Modify the CloudWatch metric policies to allow the PutMetricData permission to instances from the Auto Scaling group.

3.   Create an IAM role with PutMetricData permission and modify the Auto Scaling launching configuration to launch instances using that role.


### A Developer is working on an application that tracks hundreds of millions of product reviews in an Amazon DynamoDB table. The records include the data elements shown in the table. Which field, when used as the partition key, would result in the MOST consistent performance using DynamoDB?

<details>
<summary>Click to answer</summary>

- [x] reviewID.   

</details>

0.   starRating.

1.   reviewID.

2.   comment.

3.   productID.


### A development team consists of 10 team members. Similar to a home directory for each team member, the manager wants to grant access to user-specific folders in an Amazon S3 bucket. For the team member with the username 'TeamMemberX', the snippet of the IAM policy looks like this. Instead of creating distinct policies for each team member, what approach can be used to make this policy snippet generic for all team members?

<details>
<summary>Click to answer</summary>

- [x] Use IAM policy condition.   

</details>

0.   Use IAM policy condition.

1.   Use IAM policy principal.

2.   Use IAM policy variables.

3.   Use IAM policy resource.


### A company needs to encrypt data at rest, but it wants to leverage an AWS managed service using its own master key. Which of the following AWS service can be used to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] SSE with AWS KMS.   

</details>

0.   SSE with Amazon S3.

1.   SSE with AWS KMS.

2.   Client-side encryption.

3.   AWS IAM roles and policies.


### A Developer has created a software package to be deployed on multiple EC2 instances using IAM roles. What actions could be performed to verify IAM access to get records from Amazon Kinesis Streams? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Perform a get action using the ''-dry-run argument.
- [x] Validate the IAM role policy with the IAM policy simulator.   

</details>

0.   Use the AWS CLI to retrieve the IAM group.

1.   Query Amazon EC2 metadata for in-line IAM policies.

2.   Request a token from AWS STS, and perform a describe action.

3.   Perform a get action using the ''-dry-run argument.

4.   Validate the IAM role policy with the IAM policy simulator.


### A company wants to implement a continuous integration for its workloads on AWS. The company wants to trigger unit test in its pipeline for commits-on its code repository, and wants to be notified of failure events in the pipeline. How can these requirements be met?

<details>
<summary>Click to answer</summary>

- [x] Store the source code in AWS CodeCommit. Create a CodePipeline to automate unit testing. Use Amazon SNS to trigger notifications of failure events.   

</details>

0.   Store the source code in AWS CodeCommit. Create a CodePipeline to automate unit testing. Use Amazon SNS to trigger notifications of failure events.

1.   Store the source code in GitHub. Create a CodePipeline to automate unit testing. Use Amazon SES to trigger notifications of failure events.

2.   Store the source code on GitHub. Create a CodePipeline to automate unit testing. Use Amazon CloudWatch to trigger notifications of failure events.

3.   Store the source code in AWS CodeCommit. Create a CodePipeline to automate unit testing. Use Amazon CloudWatch to trigger notification of failure events.


### An application takes 40 seconds to process instructions received in an Amazon SQS message. Assuming the SQS queue is configured with the default VisibilityTimeout value, what is the BEST way, upon receiving a message, to ensure that no other instances can retrieve a message that has already been processed or is currently being processed?

<details>
<summary>Click to answer</summary>

- [x] Use the ChangeMessageVisibility API to increase the VisibilityTimeout, then use the DeleteMessage API to delete the message.   

</details>

0.   Use the ChangeMessageVisibility API to increase the VisibilityTimeout, then use the DeleteMessage API to delete the message.

1.   Use the DeleteMessage API call to delete the message from the queue, then call DeleteQueue API to remove the queue.

2.   Use the ChangeMessageVisibility API to decrease the timeout value, then use the DeleteMessage API to delete the message.

3.   Use the DeleteMessageVisibility API to cancel the VisibilityTimeout, then use the DeleteMessage API to delete the message.


### A Developer is developing an application that manages financial transactions. To improve security, multi-factor authentication (MFA) will be required as part of the login protocol. What services can the Developer use to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] AWS IAM with MFA enabled.   

</details>

0.   Amazon DynamoDB to store MFA session data, and Amazon SNS to send MFA codes.

1.   Amazon Cognito with MFA.

2.   AWS Directory Service.

3.   AWS IAM with MFA enabled.


### A Developer is writing transactions into a DynamoDB table called 'SystemUpdates' that has 5 write capacity units. Which option has the highest read throughput?

<details>
<summary>Click to answer</summary>

- [x] Strongly consistent reads of 5 read capacity units reading items that are 4 KB in size.   

</details>

0.   Eventually consistent reads of 5 read capacity units reading items that are 4 KB in size.

1.   Strongly consistent reads of 5 read capacity units reading items that are 4 KB in size.

2.   Eventually consistent reads of 15 read capacity units reading items that are 1 KB in size.

3.   Strongly consistent reads of 15 read capacity units reading items that are 1 KB in size.


### A Developer has created an S3 bucket s3://mycoolapp and has enabled server across logging that points to the folder s3://mycoolapp/logs.The Developer moved 100 KB of Cascading Style Sheets (CSS) documents to the folder s3://mycoolapp/css, and then stopped work. When the developer came back a few days later, the bucket was 50 GB. What is the MOST likely cause of this situation?

<details>
<summary>Click to answer</summary>

- [x] S3 replication was enabled on the bucket.   

</details>

0.   The CSS files were not compressed and S3 versioning was enabled.

1.   S3 replication was enabled on the bucket.

2.   Logging into the same bucket caused exponential log growth.

3.   An S3 lifecycle policy has moved the entire CSS file to S3 Infrequent Access.


### A Developer is testing a Docker-based application that uses the AWS SDK to interact with Amazon DynamoDB. In the local development environment, the application has used IAM access keys. The application is now ready for deployment onto an ECS cluster. How should the application authenticate with AWS services in production?

<details>
<summary>Click to answer</summary>

- [x] Configure an ECS task IAM role for the application to use.   

</details>

0.   Configure an ECS task IAM role for the application to use.

1.   Refactor the application to call AWS STS AssumeRole based on an instance role.

2.   Configure AWS access key/secret access key environment variables with new credentials.

3.   Configure the credentials file with a new access key/secret access key.


### A company is using AWS CodeBuild to compile a website from source code stored in AWS CodeCommit. A recent change to the source code has resulted in the CodeBuild project being unable to successfully compile the website. How should the Developer identify the cause of the failures?

<details>
<summary>Click to answer</summary>

- [x] Check the build logs of the failed phase in the last build attempt in the AWS CodeBuild project build history.   

</details>

0.   Modify the buildspec.yml file to include steps to send the output of build commands to Amazon CloudWatch.

1.   Use a custom Docker image that includes the AWS X-Ray agent in the AWS CodeBuild project configuration.

2.   Check the build logs of the failed phase in the last build attempt in the AWS CodeBuild project build history.

3.   Manually re-run the build process on a local machine so that the output can be visualized.


### For a deployment using AWS CodeDeploy, what is the run order of the hooks for in-place deployments?

<details>
<summary>Click to answer</summary>

- [x] Application Stop -> Before Install -> After Install -> Application Start.   

</details>

0.   Before Install -> Application Stop -> Application Start -> After Install.

1.   Application Stop -> Before Install -> After Install -> Application Start.

2.   Before Install -> Application Stop -> Validate Service -> Application Start.

3.   Application Stop -> Before Install -> Validate Service -> Application Start.


### A Developer executed a AWS CLI command and received the error shown below. What action should the Developer perform to make this error human-readable?

<details>
<summary>Click to answer</summary>

- [x] Use the AWS STS decode-authorization-message API to decode the message.   

</details>

0.   Make a call to AWS KMS to decode the message.

1.   Use the AWS STS decode-authorization-message API to decode the message.

2.   Use an open source decoding library to decode the message.

3.   Use the AWS IAM decode-authorization-message API to decode this message.


### A Developer uses AWS CodeDeploy to automate application deployment that connects to an external MySQL database. The Developer wants to securely access the encrypted secrets, such as API keys and database passwords. Which of the following solutions would involve the LEAST administrative effort?

<details>
<summary>Click to answer</summary>

- [x] Save the secrets in Amazon S3 with AWS KMS server-side encryption, and use a signed URL to access them by using the IAM role from Amazon EC2 instances.   

</details>

0.   Save the secrets in Amazon S3 with AWS KMS server-side encryption, and use a signed URL to access them by using the IAM role from Amazon EC2 instances.

1.   Use the instance metadata to store the secrets and to programmatically access the secrets from EC2 instances.

2.   Use the Amazon DynamoDB client-side encryption library to save the secrets in DynamoDB and to programmatically access the secrets from EC2 instances.

3.   Use AWS SSM Parameter Store to store the secrets and to programmatically access them by using the IAM role from EC2 instances.


### An application stops working with the following error: The specified bucket does not exist. Where is the BEST place to start the root cause analysis?

<details>
<summary>Click to answer</summary>

- [x] Check AWS CloudTrail for a DeleteBucket event.   

</details>

0.   Check the Elastic Load Balancer logs for DeleteBucket requests.

1.   Check the application logs in Amazon CloudWatch Logs for Amazon S3 DeleteBucket errors.

2.   Check AWS X-Ray for Amazon S3 DeleteBucket alarms.

3.   Check AWS CloudTrail for a DeleteBucket event.


### A Developer will be using the AWS CLI on a local development server to manage AWS services. What can be done to ensure that the CLI uses the Developer's IAM permissions when making commands?

<details>
<summary>Click to answer</summary>

- [x] Run the aws configure CLI command, and provide the Developer's IAM access key ID and secret access key.   

</details>

0.   Specify the Developer's IAM access key ID and secret access key as parameters for each CLI command.

1.   Run the aws configure CLI command, and provide the Developer's IAM access key ID and secret access key.

2.   Specify the Developer's IAM user name and password as parameters for each CLI command.

3.   Use the Developer's IAM role when making the CLI command.


### An application stores images in an S3 bucket. Amazon S3 event notifications are used to trigger a Lambda function that resizes the images. Processing each image takes less than a second. How will AWS Lambda handle the additional traffic?

<details>
<summary>Click to answer</summary>

- [x] Lambda will scale out to execute the requests concurrently.   

</details>

0.   Lambda will scale out to execute the requests concurrently.

1.   Lambda will handle the requests sequentially in the order received.

2.   Lambda will process multiple images in a single execution.

3.   Lambda will add more compute to each execution to reduce processing time.


### A company is building a stock trading application that requires sub-millisecond latency in processing trading requests. Amazon DynamoDB is used to store all the trading data that is used to process each request. After load testing the application, the development team found that due to data retrieval times, the latency requirement is not satisfied. Because of sudden high spikes in the number of requests, DynamoDB read capacity has to be significantly over-provisioned to avoid throttling. What steps should be taken to meet latency requirements and reduce the cost of running the application?

<details>
<summary>Click to answer</summary>

- [x] Add Global Secondary Indexes for trading data.   

</details>

0.   Add Global Secondary Indexes for trading data.

1.   Store trading data in Amazon S3 and use Transfer Acceleration.

2.   Add retries with exponential back-off for DynamoDB queries.

3.   Use DynamoDB Accelerator to cache trading data.


### A Developer created a Lambda function for a web application backend. When testing the Lambda function from the AWS Lambda console, the Developer can see that the function is being executed, but there is no log data being generated in Amazon CloudWatch Logs, even after several minutes. What could cause this situation?

<details>
<summary>Click to answer</summary>

- [x] The execution role for the Lambda function is missing permissions to write log data to the CloudWatch Logs.   

</details>

0.   The Lambda function does not have any explicit log statements for the log data to send it to CloudWatch Logs.

1.   The Lambda function is missing CloudWatch Logs as a source trigger to send log data.

2.   The execution role for the Lambda function is missing permissions to write log data to the CloudWatch Logs.

3.   The Lambda function is missing a target CloudWatch Log group.


### A Developer wants to use AWS X-Ray to trace a user request end-to-end throughput the software stack. The Developer made the necessary changes in the application tested it, and found that the application is able to send the traces to AWS X-Ray. However, when the application is deployed to an EC2 instance, the traces are not availableWhich of the following could create this situation? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] The X-Ray daemon is not installed on the EC2 instance.
- [x] The instance role does not have 'xray:PutTraceSegments' and 'xray:PutTelemetryRecords' permissions.   

</details>

0.   The traces are reaching X-Ray, but the Developer does not have access to view the records.

1.   The X-Ray daemon is not installed on the EC2 instance.

2.   The X-Ray endpoint specified in the application configuration is incorrect.

3.   The instance role does not have 'xray:BatchGetTraces' and 'xray:GetTraceGraph' permissions.The instance role does not have 'xray:PutTraceSegments' and 'xray:PutTelemetryRecords' permissions.

4.   The instance role does not have 'xray:PutTraceSegments' and 'xray:PutTelemetryRecords' permissions.


### An application has hundreds of users. Each user may use multiple devices to access the application. The Developer wants to assign unique identifiers to these users regardless of the device they use. Which of the following methods should be used to obtain unique identifiers?

<details>
<summary>Click to answer</summary>

- [x] Assign IAM users and roles to the users. Use the unique IAM resource ID as the unique identifier.   

</details>

0.   Create a user table in Amazon DynamoDB as key-value pairs of users and their devices. Use these keys as unique identifiers.

1.   Use IAM-generated access key IDs for the users as the unique identifier, but do not store secret keys.

2.   Implement developer-authenticated identities by using Amazon Cognito, and get credentials for these identities.

3.   Assign IAM users and roles to the users. Use the unique IAM resource ID as the unique identifier.


### What are the steps to using the AWS CLI to launch a templatized serverless application?

<details>
<summary>Click to answer</summary>

- [x] Use AWS CloudFormation package then CloudFormation deploy.   

</details>

0.   Use AWS CloudFormation get-template then CloudFormation execute-change-set.

1.   Use AWS CloudFormation validate-template then CloudFormation create-change-set.

2.   Use AWS CloudFormation package then CloudFormation deploy.

3.   Use AWS CloudFormation create-stack then CloudFormation update-stack.


### A deployment package uses the AWS CLI to copy files into any S3 bucket in the account, using access keys stored in environment variables. The package is running on EC2 instances, and the instances have been modified to run with an assumed IAM role and a more restrictive policy that allows access to only one bucket. After the change, the Developer logs into the host and still has the ability to write into all of the S3 buckets in that account. What is the MOST likely cause of this situation?

<details>
<summary>Click to answer</summary>

- [x] An IAM managed policy is being used on the IAM role.   

</details>

0.   An IAM inline policy is being used on the IAM role.

1.   An IAM managed policy is being used on the IAM role.

2.   The AWS CLI is corrupt and needs to be reinstalled.

3.   The AWS credential provider looks for instance profile credentials last.


### An application overwrites an object in Amazon S3, and then immediately reads the same object. Why would the application sometimes retrieve the old version of the object?

<details>
<summary>Click to answer</summary>

- [x] S3 overwrite PUTS are eventually consistent, so the application may read the old object.   

</details>

0.   S3 overwrite PUTS are eventually consistent, so the application may read the old object.

1.   The application needs to add extra metadata to label the latest version when uploading to Amazon S3.

2.   All S3 PUTS are eventually consistent, so the application may read the old object.

3.   The application needs to explicitly specify latest version when retrieving the object.


### An application under development is required to store hundreds of video files. The data must be encrypted within the application prior to storage, with a unique key for each video file. How should the Developer code the application?

<details>
<summary>Click to answer</summary>

- [x] Use the KMS GenerateDataKey API to get a data key. Encrypt the data with the data key. Store the encrypted data key and data.   

</details>

0.   Use the KMS Encrypt API to encrypt the data. Store the encrypted data key and data.

1.   Use a cryptography library to generate an encryption key for the application. Use the encryption key to encrypt the data. Store the encrypted data.

2.   Use the KMS GenerateDataKey API to get a data key. Encrypt the data with the data key. Store the encrypted data key and data.

3.   Upload the data to an S3 bucket using server side-encryption with an AWS KMS key.


### A developer is testing an application that invokes an AWS Lambda function asynchronously. During the testing phase, the Lambda function fails to process after two retries. How can the developer troubleshoot the failure?

<details>
<summary>Click to answer</summary>

- [x] Configure Dead Letter Queues by sending events to Amazon SQS for investigatio.   

</details>

0.   Configure AWS CloudTrail logging to investigate the invocation failures.

1.   Configure Dead Letter Queues by sending events to Amazon SQS for investigatio.

2.   Configure Amazon Simple Workflow Service to process any direct unprocessed events.

3.   Configure AWS Config to process any direct unprocessed events.


### A developer is setting up Amazon API Gateway for their company's products. The API will be used by registered developers to query and update their environments. The company wants to limit the amount of requests end users can send for both cost and security reasons. Management wants to offer registered developers the option of buying larger packages that allow for more requests. How can the developer accomplish this with the LEAST amount of overhead management?

<details>
<summary>Click to answer</summary>

- [x] Set up a default usage plan, specify values for the rate and burst capacity, and associate it with a stage. If a registered user chooses a larger package, create a custom plan with the appropriate values and associate the plan with the user.   

</details>

0.   Enable throttling for the API Gateway stage. Set a value for both the rate and burst capacity. If a registered user chooses a larger package, create a stage for them, adjust the values, and share the new URL with them.

1.   Set up Amazon CloudWatch API logging in API Gateway. Create a filter based on the user and requestTime fields and create an alarm on this filter. Write an AWS Lambda function to analyze the values and requester information, and respond accordingly. Set up the function as the target for the alarm. If a registered user chooses a larger package, update the Lambda code with the values.

2.   Enable Amazon CloudWatch metrics for the API Gateway stage. Set up CloudWatch alarms based off the Count metric and the ApiName, Method, Resource, and Stage dimensions to alerts when request rates pass the threshold. Set the alarm action to Deny. If a registered user chooses a larger package, create a user-specific alarm and adjust the values.

3.   Set up a default usage plan, specify values for the rate and burst capacity, and associate it with a stage. If a registered user chooses a larger package, create a custom plan with the appropriate values and associate the plan with the user.


### A developer is refactoring a monolithic application. The application takes a POST request and performs several operations. Some of the operations are in parallel while others run sequentially. These operations have been refactored into individual AWS Lambda functions. The POST request will be processed by Amazon API Gateway. How should the developer invoke the Lambda functions in the same sequence using API Gateway?

<details>
<summary>Click to answer</summary>

- [x] Use an AWS Step Functions state machine to orchestrate the Lambda functions.   

</details>

0.   Use Amazon SQS to invoke the Lambda functions.

1.   Use an AWS Step Functions activity to run the Lambda functions.

2.   Use Amazon SNS to trigger the Lambda functions.

3.   Use an AWS Step Functions state machine to orchestrate the Lambda functions.


### A company is adding stored value (or gift card) capability to its highly popular casual gaming website. Users need to be able to trade this value for other users' items on the platform. This would require both users' records be updated as a single transaction, or both users' records to be completely rolled back. Which AWS database options can provide the transactional capability required for this new feature? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Amazon ElastiCache for Memcached with operations made within a transaction block.
- [x] Amazon DynamoDB with reads and writes made using Transact* operations.   

</details>

0.   Amazon DynamoDB with operations made with the ConsistentRead parameter set to true.

1.   Amazon ElastiCache for Memcached with operations made within a transaction block.

2.   Amazon Aurora MySQL with operations made within a transaction block.

3.   Amazon DynamoDB with reads and writes made using Transact* operations.

4.   Amazon Redshift with operations made within a transaction block.


### A developer is creating an AWS Lambda function that generates a new file each time it runs. Each new file must be checked into an AWS CodeCommit repository hosted in the same AWS account. How should the developer accomplish this?

<details>
<summary>Click to answer</summary>

- [x] When the Lambda function starts, use the Git CLI to clone the repository. Check the new file into the cloned repository and push the change.   

</details>

0.   When the Lambda function starts, use the Git CLI to clone the repository. Check the new file into the cloned repository and push the change.

1.   After the new file is created in Lambda, use cURL to invoke the CodeCommit API. Send the file to the repository.

2.   Use an AWS SDK to instantiate a CodeCommit client. Invoke the put_file method to add the file to the repository.

3.   Upload the new to an Amazon S3 bucket. Create an AWS Step Function to accept S3 events. In the Step Function, add the new file to the repository.


### A developer must ensure that the IAM credentials used by an application in Amazon EC2 are not misused or compromised. What should the developer use to keep user credentials secure?

<details>
<summary>Click to answer</summary>

- [x] Command line options.   

</details>

0.   Environment variables.

1.   AWS credentials file.

2.   Instance profile credentials.

3.   Command line options.


### A company has an application where reading objects from Amazon S3 is based on the type of user. The user types are registered user and guest user. The company has 25,000 users and is growing. Information is pulled from an S3 bucket depending on the user type. Which approaches are recommended to provide access to both user types? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Provide a different access key and secret access key in the application code for registered users and guest users to provide read access to the objects.
- [x] Use S3 bucket policies to restrict read access to specific IAM users.   

</details>

0.   Provide a different access key and secret access key in the application code for registered users and guest users to provide read access to the objects.

1.   Use S3 bucket policies to restrict read access to specific IAM users.

2.   Use Amazon Cognito to provide access using authenticated and unauthenticated roles.

3.   Create a new IAM user for each user and grant read access.

4.   Use the AWS IAM service and let the application assume the different roles using the AWS Security Token Service (AWS STS) AssumeRole action depending on the type of user and provide read access to Amazon S3 using the assumed role.


### A company has 25,000 employees and is growing. The company is creating an application that will be accessible to its employees only. A developer is using Amazon S3 to store images and Amazon RDS to store application data. The company requires that all employee information remain in the legacy Security Assertion Markup Language (SAML) employee directory only and is not interested in mirroring any employee information on AWS. How can the developer provide authorized access for the employees who will be using this application so each employee can access their own application data only?

<details>
<summary>Click to answer</summary>

- [x] Use an Amazon Cognito identity pool, federate with the SAML provider, and use an IAM condition key with a value for the cognito-identity.amazonaws.com:sub variable to grant access to the employees.   

</details>

0.   Use Amazon VPC and keep all resources inside the VPC, and use a VPC link for the S3 bucket with the bucket policy.

1.   Use Amazon Cognito user pools, federate with the SAML provider, and use user pool groups with an IAM policy.

2.   Use an Amazon Cognito identity pool, federate with the SAML provider, and use an IAM condition key with a value for the cognito-identity.amazonaws.com:sub variable to grant access to the employees.

3.   Create a unique IAM role for each employee and have each employee assume the role to access the application so they can access their personal data only.


### A company has developed a new serverless application using AWS Lambda functions that will be deployed using the AWS Serverless Application Model (AWS SAM) CLI. Which step should the developer complete prior to deploying the application?

<details>
<summary>Click to answer</summary>

- [x] Compress the application to a .zip file and upload it into AWS Lambda.   

</details>

0.   Compress the application to a .zip file and upload it into AWS Lambda.

1.   Test the new AWS Lambda function by first tracing it in AWS X-Ray.

2.   Bundle the serverless application using a SAM package.

3.   Create the application environment using the eb create my-env command.


### An application needs to encrypt data that is written to Amazon S3 where the keys are managed in an on-premises data center, and the encryption is handled by S3. Which type of encryption should be used?

<details>
<summary>Click to answer</summary>

- [x] Use client-side encryption with customer master keys.   

</details>

0.   Use server-side encryption with Amazon S3-managed keys.

1.   Use server-side encryption with AWS KMS-managed keys.

2.   Use client-side encryption with customer master keys.

3.   Use server-side encryption with customer-provided keys.


### A development team is working on a mobile app that allows users to upload pictures to Amazon S3. The team expects the app will be used by hundreds of thousands of users during a single event simultaneously. Once the pictures are uploaded, the backend service will scan and parse the pictures for inappropriate content. Which approach is the MOST resilient way to achieve this goal, which also smooths out temporary volume spikes for the backend service?

<details>
<summary>Click to answer</summary>

- [x] Once a picture is uploaded to Amazon S3, publish the event to an Amazon SQS queue. Use the queue as an event source to trigger an AWS Lambda function. In the Lambda function, scan and parse the picture.   

</details>

0.   Develop an AWS Lambda function to check the upload folder in the S3 bucket. If new uploaded pictures are detected, the Lambda function will scan and parse them.

1.   Once a picture is uploaded to Amazon S3, publish the event to an Amazon SQS queue. Use the queue as an event source to trigger an AWS Lambda function. In the Lambda function, scan and parse the picture.

2.   When the user uploads a picture, invoke an API hosted in Amazon API Gateway. The API will invoke an AWS Lambda function to scan and parse the picture.

3.   Create a state machine in AWS Step Functions to check the upload folder in the S3 bucket. If a new picture is detected, invoke an AWS Lambda function to scan and parse it.


### A development team wants to run their container workloads on Amazon ECS. Each application container needs to share data with another container to collect logs and metrics. What should the developer team do to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Create two pod specifications. Make one to include the application container and the other to include the other container. Link the two pods together.   

</details>

0.   Create two pod specifications. Make one to include the application container and the other to include the other container. Link the two pods together.

1.   Create two task definitions. Make one to include the application container and the other to include the other container. Mount a shared volume between the two tasks.

2.   Create one task definition. Specify both containers in the definition. Mount a shared volume between those two containers.

3.   Create a single pod specification. Include both containers in the specification. Mount a persistent volume to both containers.


### An ecommerce startup is preparing for an annual sales event. As the traffic to the company's application increases, the development team wants to be notified when the Amazon EC2 instance's CPU utilization exceeds 80%. Which solution will meet this requirement?

<details>
<summary>Click to answer</summary>

- [x] Create a custom Amazon CloudWatch alarm that sends a notification to an Amazon SNS topic when the CPU utilization exceeds 80%.   

</details>

0.   Create a custom Amazon CloudWatch alarm that sends a notification to an Amazon SNS topic when the CPU utilization exceeds 80%.

1.   Create a custom AWS Cloud Trail alarm that sends a notification to an Amazon SNS topic when the CPU utilization exceeds 80%.

2.   Create a cron job on the EC2 instance that executes the –describe-instance-information command on the host instance every 15 minutes and sends the results to an Amazon SNS topic.

3.   Create an AWS Lambda function that queries the AWS CloudTrail logs for the CPUUtilization metric every 15 minutes and sends a notification to an Amazon SNS topic when the CPU utilization exceeds 80%.


### An application running on Amazon EC2 opens connections to an Amazon RDS SQL Server database. The developer does not want to store the user name and password for the database in the code. The developer would also like to automatically rotate the credentials. What is the MOST secure way to store and access the database credentials?

<details>
<summary>Click to answer</summary>

- [x] Use AWS Secrets Manager to store the credentials. Retrieve the credentials from Secrets Manager as needed.   

</details>

0.   Create an IAM role that has permissions to access the database. Attach the role to the EC2 instance.

1.   Use AWS Secrets Manager to store the credentials. Retrieve the credentials from Secrets Manager as needed.

2.   Store the credentials in an encrypted text file in an Amazon S3 bucket. Configure the EC2 instance's user data to download the credentials from Amazon S3 as the instance boots.

3.   Store the user name and password credentials directly in the source code. No further action is needed because the source code is stored in a private repository.


### A developer is updating an application deployed on AWS Elastic Beanstalk. The new version is incompatible with the old version. To successfully deploy the update, a full cutover to the new, updated version must be performed on all instances at one time, with the ability to roll back changes in case of a deployment failure in the new version. How can this be performed with the LEAST amount of downtime?

<details>
<summary>Click to answer</summary>

- [x] Perform an Elastic Beanstalk Rolling deployment.   

</details>

0.   Use the Elastic Beanstalk All at once deployment policy to update all instances simultaneously.

1.   Perform an Elastic Beanstalk Rolling with additional batch deployment.

2.   Deploy the new version in a new Elastic Beanstalk environment and swap environment URLs.

3.   Perform an Elastic Beanstalk Rolling deployment.


### A developer is writing a web application that must share secure documents with end users. The documents are stored in a private Amazon S3 bucket. The application must allow only authenticated users to download specific documents when requested, and only for a duration of 15 minutes. How can the developer meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Create a presigned S3 URL using the AWS SDK with an expiration time of 15 minutes.   

</details>

0.   Copy the documents to a separate S3 bucket that has a lifecycle policy for deletion after 15 minutes.

1.   Create a presigned S3 URL using the AWS SDK with an expiration time of 15 minutes.

2.   Create a presigned S3 URL using the AWS SDK with an expiration time of 15 minutes.

3.   Create a presigned S3 URL using the AWS SDK with an expiration time of 15 minutes.


### A company is developing a report executed by AWS Step Functions, Amazon CloudWatch shows errors in the Step Functions task state machine. To troubleshoot each task, the state input needs to be included along with the error message in the state output. Which coding practice can preserve both the original input and the error for the state?

<details>
<summary>Click to answer</summary>

- [x] Use ResultPath in a Catch statement to include the error with the original input.   

</details>

0.   Use ResultPath in a Catch statement to include the error with the original input.

1.   Use InputPath in a Catch statement and set the value to null.

2.   Use Error Equals in a Retry statement to include the error with the original input.

3.   Use OutputPath in a Retry statement and set the value to $.


### A developer receives the following error message when trying to launch or terminate an Amazon EC2 instance using a boto3 script. What should the developer do to correct this error message?

<details>
<summary>Click to answer</summary>

- [x] Implement an exponential backoff algorithm for optimizing the number of API requests made to Amazon EC2.   

</details>

0.   Assign an IAM role to the EC2 instance to allow necessary API calls on behalf of the client.

1.   Implement an exponential backoff algorithm for optimizing the number of API requests made to Amazon EC2.

2.   Increase the overall network bandwidth to handle higher API request rates.

3.   Upgrade to the latest AWS CLI version so that boto3 can handle higher request rates.


### Given the following AWS CloudFormation template. What is the MOST efficient way to reference the new Amazon S3 bucket from another AWS CloudFormation template?

<details>
<summary>Click to answer</summary>

- [x] Create a custom AWS CloudFormation resource that gets the bucket name from the ContentBucket resource of the first stack.   

</details>

0.   Add an Export declaration to the Outputs section of the original template and use ImportValue in other templates.

1.   Add Exported: true to the Contentbucket in the original template and use ImportResource in other templates.

2.   Create a custom AWS CloudFormation resource that gets the bucket name from the ContentBucket resource of the first stack.

3.   Use Fn::Include to include the existing template in other templates and use the ContentBucket resource directly.


### A developer is using AWS CodeDeploy to deploy an application running on Amazon EC2. The developer wants to change the file permissions for a specific deployment file. Which lifecycle event should a developer use to meet this requirement?

<details>
<summary>Click to answer</summary>

- [x] AfterInstall.   

</details>

0.   AfterInstall.

1.   DownloadBundle.

2.   BeforeInstall.

3.   ValidateService.


### A developer is using Amazon DynamoDB to store application data. The developer wants to further improve application performance by reducing response times for read and write operations. Which DynamoDB feature should be used to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Amazon DynamoDB transactions.   

</details>

0.   Amazon DynamoDB Streams.

1.   Amazon DynamoDB Accelerator.

2.   Amazon DynamoDB global tables.

3.   Amazon DynamoDB transactions.


### A developer is creating a script to automate the deployment process for a serverless application. The developer wants to use an existing AWS Serverless Application Model (AWS SAM) template for the application. What should the developer use for the project? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Call aws s3 cp to upload the AWS SAM template to Amazon S3. Call aws lambda update-function-code to create the application.
- [x] Create a ZIP package and upload it to Amazon S3. Call aws cloudformation create-stack to create the application.   

</details>

0.   Call aws cloudformation package to create the deployment package. Call aws cloudformation deploy to deploy the package afterward.

1.   Call sam package to create the deployment package. Call sam deploy to deploy the package afterward.

2.   Call aws s3 cp to upload the AWS SAM template to Amazon S3. Call aws lambda update-function-code to create the application.

3.   Create a ZIP package locally and call aws serverlessrepo create-application to create the application.

4.   Create a ZIP package and upload it to Amazon S3. Call aws cloudformation create-stack to create the application.


### A development team is designing a mobile app that requires multi-factor authentication. Which steps should be taken to achieve this? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Enable multi-factor authentication for the Amazon Cognito user pool.
- [x] Enable multi-factor authentication for the users created in AWS IAM.   

</details>

0.   Use Amazon Cognito to create a user pool and create users in the user pool.

1.   Send multi-factor authentication text codes to users with the Amazon SNS Publish API call in the app code.

2.   Enable multi-factor authentication for the Amazon Cognito user pool.

3.   Use AWS IAM to create IAM users.

4.   Enable multi-factor authentication for the users created in AWS IAM.


### Two containerized microservices are hosted on Amazon EC2 ECS. The first microservice reads an Amazon RDS Aurora database instance, and the second microservice reads an Amazon DynamoDB table. How can each microservice be granted the minimum privileges?

<details>
<summary>Click to answer</summary>

- [x] Set ECS_ENABLE_TASK_IAM_ROLE to true on EC2 instance boot in the ECS agent configuration file. Run the first microservice with an IAM role for ECS tasks with read-only access for the Aurora database. Run the secondmicroservice with an IAM role for ECS tasks with read-only access to DynamoDB.   

</details>

0.   Set ECS_ENABLE_TASK_IAM_ROLE to false on EC2 instance boot in ECS agent configuration file. Run the first microservice with an IAM role for ECS tasks with read-only access for the Aurora database. Run the second microservice with an IAM role for ECS tasks with read-only access to DynamoDB.

1.   Set ECS_ENABLE_TASK_IAM_ROLE to false on EC2 instance boot in the ECS agent configuration file. Grant the instance profile role read-only access to the Aurora database and DynamoDB.

2.   Set ECS_ENABLE_TASK_IAM_ROLE to true on EC2 instance boot in the ECS agent configuration file. Run the first microservice with an IAM role for ECS tasks with read-only access for the Aurora database. Run the secondmicroservice with an IAM role for ECS tasks with read-only access to DynamoDB.

3.   Set ECS_ENABLE_TASK_IAM_ROLE to true on EC2 instance boot in the ECS agent configuration file. Grant the instance profile role read-only access to the Aurora database and DynamoDB.


### A developer has written an AWS Lambda function using Java as the runtime environment. The developer wants to isolate a performance bottleneck in the code. Which steps should be taken to reveal the bottleneck?

<details>
<summary>Click to answer</summary>

- [x] Use the AWS X-Ray API to write trace data into X-Ray from strategic places within the code. Use the Amazon CloudWatch console to analyze the resulting data.   

</details>

0.   Use the Amazon CloudWatch API to write timestamps to a custom CloudWatch metric. Use the CloudWatch console to analyze the resulting data.

1.   Use the AWS X-Ray API to write trace data into X-Ray from strategic places within the code. Use the Amazon CloudWatch console to analyze the resulting data.

2.   Use the AWS X-Ray API to write trace data into X-Ray from strategic places within the code. Use the X-Ray console to analyze the resulting data.

3.   Use the Amazon CloudWatch API to write timestamps to a custom CloudWatch metric. Use the AWS X-Ray console to analyze the resulting data.


### A developer added a new feature to an application running on an Amazon EC2 instance that uses Amazon SQS. After deployment, the developer noticed a significant increase in Amazon SQS costs. When monitoring the Amazon SQS metrics on Amazon CloudWatch, the developer found that on average one message per minute is posted on this queue. What can be done to reduce Amazon SQS costs for this application?

<details>
<summary>Click to answer</summary>

- [x] Increase the Amazon SQS queue polling timeout.   

</details>

0.   Increase the Amazon SQS queue polling timeout.

1.   Scale down the Amazon SQS queue to the appropriate size for low traffic demand.

2.   Configure push delivery via Amazon SNS instead of polling the Amazon SQS queue.

3.   Use an Amazon SQS first-in, first-out (FIFO) queue instead of a standard queue.


### A developer is building an application using an Amazon API Gateway REST API backend by an AWS Lambda function that interacts with an Amazon DynamoDB table. During testing, the developer observes high latency when making requests to the API. How can the developer evaluate the end-to-end latency and identify performance bottlenecks?

<details>
<summary>Click to answer</summary>

- [x] Enable and configure AWS X-Ray tracing on API Gateway and the Lambda function. Use X-Ray to trace and analyze user requests.   

</details>

0.   Enable AWS CloudTrail logging and use the logs to map each latency and bottleneck.

1.   Enable and configure AWS X-Ray tracing on API Gateway and the Lambda function. Use X-Ray to trace and analyze user requests.

2.   Enable Amazon CloudWatch Logs for the Lambda function. Enable execution logs for API Gateway to view and analyze user request logs.

3.   Enable VPC Flow Logs to capture and analyze network traffic within the VPC.


### An IAM role is attached to an Amazon EC2 instance that explicitly denies access to all Amazon S3 API actions. The EC2 instance credentials file specifies the IAM access key and secret access key, which allow full administrative access. Given that multiple modes of IAM access are present for this EC2 instance, which of the following is correct?

<details>
<summary>Click to answer</summary>

- [x] The EC2 instance will only be able to list the S3 buckets.   

</details>

0.   The EC2 instance will only be able to list the S3 buckets.

1.   The EC2 instance will only be able to list the contents of one S3 bucket at a time.

2.   The EC2 instance will be able to perform all actions on any S3 bucket.

3.   The EC2 instance will not be able to perform any S3 action on any S3 bucket.


### A development team uses AWS Elastic Beanstalk for application deployment. The team has configured the application version lifecycle policy to limit the number of application versions to 25. However, even with the lifecycle policy, the source bundle is deleted from the Amazon S3 source bucket. What should a developer do in the Elastic Beanstalk application version lifecycle settings to retain the source code in the S3 bucket?

<details>
<summary>Click to answer</summary>

- [x] Set Retention to Retain source bundle in S3.   

</details>

0.   Change the Set the application versions limit by total count setting to zero.

1.   Disable the Lifecycle policy setting.

2.   Change the Set the application version limit by age setting to zero.

3.   Set Retention to Retain source bundle in S3.


### A developer has built a market application that stores pricing data in Amazon DynamoDB with Amazon ElastiCache in front. The prices of items in the market change frequently. Sellers have begun complaining that, after they update the price of an item, the price does not actually change in the product listing. What could be causing this issue?

<details>
<summary>Click to answer</summary>

- [x] The cache is not being invalidated when the price of the item is changed.   

</details>

0.   The cache is not being invalidated when the price of the item is changed.

1.   The price of the item is being retrieved using a write-through ElastiCache cluster.

2.   The DynamoDB table was provisioned with insufficient read capacity.

3.   The DynamoDB table was provisioned with insufficient write capacity.


### A developer is provided with an HTTPS clone URL for an AWS CodeCommit repository. What needs to be configured before cloning this repository?

<details>
<summary>Click to answer</summary>

- [x] Set up the Git credential helper to use an AWS credential profile, and enable the helper to send the path to the repositories.   

</details>

0.   Use AWS KMS to set up public and private keys for use with AWS CodeCommit.

1.   Set up the Git credential helper to use an AWS credential profile, and enable the helper to send the path to the repositories.

2.   Use AWS Certificate Manager to provision public and private SSL/TLS certificates.

3.   Generate encryption keys using AWS CloudHSM, then export the key for use with AWS CodeCommit.


### What is required to trace Lambda-based applications with AWS X-Ray?

<details>
<summary>Click to answer</summary>

- [x] Trigger a Lambda function from the application logs in Amazon CloudWatch to submit tracing data to AWS X-Ray.   

</details>

0.   Send logs from the Lambda application to an S3 bucket; trigger a Lambda function from the bucket to send data to AWS X-Ray.

1.   Trigger a Lambda function from the application logs in Amazon CloudWatch to submit tracing data to AWS X-Ray.

2.   Use an IAM execution role to give the Lambda function permissions and enable tracing.

3.   Update and add AWS X-Ray daemon code to relevant parts of the Lambda function to set up the trace.


### A development team is building a new application that will run on Amazon EC2 and use Amazon DynamoDB as a storage layer. The developers all have assigned IAM user accounts in the same IAM group. The developers currently can launch EC2 instances, and they need to be able to launch EC2 instances with an instance role allowing access to Amazon DynamoDB. Which AWS IAM changes are needed when creating an instance role to provide this functionality?

<details>
<summary>Click to answer</summary>

- [x] Create an IAM permissions policy attached to the role that allows access to DynamoDB. Add a trust policy to the role that allows Amazon EC2 to assume the role. Attach a permissions policy to the development group in AWS IAM that allows developers to use the iam:PassRole permission for the role.   

</details>

0.   Create an IAM permission policy attached to the role that allows access to DynamoDB. Add a trust policy to the role that allows DynamoDB to assume the role. Attach a permissions policy to the development group in AWS IAM that allows developers to use the iam:GetRole and iam:PassRole permissions for the role.

1.   Create an IAM permissions policy attached to the role that allows access to DynamoDB. Add a trust policy to the role that allows Amazon EC2 to assume the role. Attach a permissions policy to the development group in AWS IAM that allows developers to use the iam:PassRole permission for the role.

2.   Create an IAM permission policy attached to the role that allows access to Amazon EC2. Add a trust policy to the role that allows DynamoDB to assume the role. Attach a permissions policy to the development group in AWS IAM that allows developers to use the iam:PassRole permission for the role.

3.   Create an IAM permissions policy attached to the role that allows access to DynamoDB. Add a trust policy to the role that allows Amazon EC2 to assume the role. Attach a permissions policy to the development group in AWS IAM that allows developers to use the iam:GetRole permission for the role.


### A developer converted an existing program to an AWS Lambda function in the console. The program runs properly on a local laptop, but shows an 'Unable to import module' error when tested in the Lambda console. Which of the following can fix the error?

<details>
<summary>Click to answer</summary>

- [x] In the Lambda console, create a LB_LIBRARY_PATH environment and specify the value for the system library plan.   

</details>

0.   Install the missing module and specify the current directory as the target. Create a ZIP file to include all files under the current directory, and upload the ZIP file.

1.   Install the missing module in a lib directory. Create a ZIP file to include all files under the lib directory, and upload the ZIP file as dependency file.

2.   In the Lambda code, invoke a Linux command to install the missing modules under the /usr/lib directory.

3.   In the Lambda console, create a LB_LIBRARY_PATH environment and specify the value for the system library plan.


### A front-end web application is using Amazon Cognito user pools to handle the user authentication flow. A developer is integrating Amazon DynamoDB into the application using the AWS SDK for JavaScript. How would the developer securely call the API without exposing the access or secret keys?

<details>
<summary>Click to answer</summary>

- [x] Configure Amazon Cognito identity pools and exchange the JSON Web Token (JWT) for temporary credentials.   

</details>

0.   Configure Amazon Cognito identity pools and exchange the JSON Web Token (JWT) for temporary credentials.

1.   Run the web application in an Amazon EC2 instance with the instance profile configured.

2.   Hardcore the credentials, use Amazon S3 to host the web application, and enable server-side encryption.

3.   Use Amazon Cognito user pool JSON Web Tokens (JWITs) to access the DynamoDB APIs.


### A developer needs to manage AWS infrastructure as code and must be able to deploy multiple identical copies of the infrastructure, stage changes, and revert to previous versions. Which approach addresses these requirements?

<details>
<summary>Click to answer</summary>

- [x] Use AWS CloudFormation and AWS CodeCommit to deploy and manage the infrastructure.   

</details>

0.   Use cost allocation reports and AWS OpsWorks to deploy and manage the infrastructure.

1.   Use Amazon CloudWatch metrics and alerts along with resource tagging to deploy and manage the infrastructure.

2.   Use AWS Elastic Beanstalk and AWS CodeCommit to deploy and manage the infrastructure.

3.   Use AWS CloudFormation and AWS CodeCommit to deploy and manage the infrastructure.


### A Developer needs to deploy an application running on AWS Fargate using Amazon ECS. The application has environment variables that must be passed to a container for the application to initialize. How should the environment variables be passed to the container?

<details>
<summary>Click to answer</summary>

- [x] Define an array that includes the environment variables under the environment parameter within the task definition.   

</details>

0.   Define an array that includes the environment variables under the environment parameter within the service definition.

1.   Define an array that includes the environment variables under the environment parameter within the task definition.

2.   Define an array that includes the environment variables under the entryPoint parameter within the task definition.

3.   Define an array that includes the environment variables under the entryPoint parameter within the service definition.


### A company's fleet of Amazon EC2 instances receives data from millions of users through an API. The servers batch the data, add an object for each user, and upload the objects to an S3 bucket to ensure high access rates. The object attributes are Customer ID, Server ID, TS-Server (TimeStamp and Server ID), the size of the object, and a timestamp. A Developer wants to find all the objects for a given user collected during a specified time range. After creating an S3 object created event, how can the Developer achieve this requirement?

<details>
<summary>Click to answer</summary>

- [x] Execute an AWS Lambda function in response to the S3 object creation events that creates an Amazon DynamoDB record for every object with the Customer ID as the partition key and TS-Server as the sort key. Retrieve all the records using the Customer ID and TS-Server attributes.   

</details>

0.   Execute an AWS Lambda function in response to the S3 object creation events that creates an Amazon DynamoDB record for every object with the Customer ID as the partition key and the Server ID as the sort key. Retrieve all the records using the Customer ID and Server ID attributes.

1.   Execute an AWS Lambda function in response to the S3 object creation events that creates an Amazon Redshift record for every object with the Customer ID as the partition key and TS-Server as the sort key. Retrieve all the records using the Customer ID and TS-Server attributes.

2.   Execute an AWS Lambda function in response to the S3 object creation events that creates an Amazon DynamoDB record for every object with the Customer ID as the partition key and TS-Server as the sort key. Retrieve all the records using the Customer ID and TS-Server attributes.

3.   Execute an AWS Lambda function in response to the S3 object creation events that creates an Amazon Redshift record for every object with the Customer ID as the partition key and the Server ID as the sort key. Retrieve all the records using the Customer ID and Server ID attributes.


### A company is managing a NoSQL database on-premises to host a critical component of an application, which is starting to have scaling issues. The company wants to migrate the application to Amazon DynamoDB with the following considerations: Optimize frequent queries. Reduce read latencies. Plan for frequent queries on certain key attributes of the table. Which solution would help achieve these objectives?

<details>
<summary>Click to answer</summary>

- [x] Create global secondary indexes on keys that are frequently queried. Add the necessary attributes into the indexes.   

</details>

0.   Create global secondary indexes on keys that are frequently queried. Add the necessary attributes into the indexes.

1.   Create local secondary indexes on keys that are frequently queried. DynamoDB will fetch needed attributes from the table.

2.   Create DynamoDB global tables to speed up query responses. Use a scan to fetch data from the table.

3.   Create an AWS Auto Scaling policy for the DynamoDB table.


### A developer is writing an application that will process data delivered into an Amazon S3 bucket. The data is delivered approximately 10 times a day, and the developer expects the data will be processed in less than 1 minute, on average. How can the developer deploy and invoke the application with the lowest cost and lowest latency?

<details>
<summary>Click to answer</summary>

- [x] Deploy the application as an AWS Lambda function and invoke it with an S3 event notification.   

</details>

0.   Deploy the application as an AWS Lambda function and invoke it with an Amazon CloudWatch alarm triggered by an S3 object upload.

1.   Deploy the application as an AWS Lambda function and invoke it with an S3 event notification.

2.   Deploy the application as an AWS Lambda function and invoke it with an Amazon CloudWatch scheduled event.

3.   Deploy the application onto an Amazon EC2 instance and have it poll the S3 bucket for new objects.


### A company is using Amazon API Gateway to manage its public-facing API. The CISO requires that the APIs be used by test account users only. What is the MOST secure way to restrict API access to users of this particular AWS account?

<details>
<summary>Click to answer</summary>

- [x] API Gateway resource policies.   

</details>

0.   Client-side SSL certificates for authentication.

1.   API Gateway resource policies.

2.   Cross-origin resource sharing (CORS).

3.   Usage plans.


### A Developer is migrating existing applications to AWS. These applications use MongoDB as their primary data store, and they will be deployed to Amazon EC2 instances. Management requires that the Developer minimize changes to applications while using AWS services. Which solution should the Developer use to host MongoDB in AWS?

<details>
<summary>Click to answer</summary>

- [x] Replicate the existing MongoDB workload to Amazon DynamoDB.   

</details>

0.   Install MongoDB on the same instance where the application is running.

1.   Deploy Amazon DocumentDB in MongoDB compatibility mode.

2.   Use Amazon API Gateway to translate API calls from MongoDB to Amazon DynamoDB.

3.   Replicate the existing MongoDB workload to Amazon DynamoDB.


### A company requires that AWS Lambda functions written by Developers log errors so System Administrators can more effectively troubleshoot issues. What should the Developers implement to meet this need?

<details>
<summary>Click to answer</summary>

- [x] Create an Amazon CloudWatch Events event trigger based on certain Lambda events.   

</details>

0.   Publish errors to a dedicated Amazon SQS queue.

1.   Create an Amazon CloudWatch Events event trigger based on certain Lambda events.

2.   Report errors through logging statements in Lambda function code.

3.   Set up an Amazon SNS topic that sends logging statements upon failure.


### A Developer is writing an application that runs on Amazon EC2 instances in an Auto Scaling group. The application data is stored in an Amazon DynamoDB table and records are constantly updated by all instances. An instance sometimes retrieves old data. The Developer wants to correct this by making sure the reads are strongly consistent. How can the Developer accomplish this?

<details>
<summary>Click to answer</summary>

- [x] Set ConsistentRead to true when calling Getltem.   

</details>

0.   Set ConsistentRead to true when calling Getltem.

1.   Create a new DynamoDB Accelerator (DAX) table.

2.   Set Consistency to strong when calling UpdateTable.

3.   Use the GetShardIterator command.


### A Developer has an application that must accept a large amount of incoming data streams and process the data before sending it to many downstream users. Which serverless solution should the Developer use to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Amazon Kinesis Data Streams with AWS Lambda.   

</details>

0.   Amazon RDS MySQL stored procedure with AWS Lambda.

1.   AWS Direct Connect with AWS Lambda.

2.   Amazon Kinesis Data Streams with AWS Lambda.

3.   Amazon EC2 bash script with AWS Lambda.


### An application is experiencing performance issues based on increased demand. This increased demand is on read-only historical records pulled from an Amazon RDS-hosted database with custom views and queries. A Developer must improve performance without changing the database structure. Which approach will improve performance and MINIMIZE management overhead?

<details>
<summary>Click to answer</summary>

- [x] Deploy Amazon ElastiCache for Redis and cache the data for the application.   

</details>

0.   Deploy Amazon DynamoDB, move all the data, and point to DynamoDB.

1.   Deploy Amazon ElastiCache for Redis and cache the data for the application.

2.   Deploy Memcached on Amazon EC2 and cache the data for the application.

3.   Deploy Amazon DynamoDB Accelerator (DAX) on Amazon RDS to improve cache performance.


### A Developer has an Amazon DynamoDB table that must be in provisioned mode to comply with user requirements. The application needs to support the following: Average item size: 10 KB Item reads each second: 10 strongly consistent Item writes each second: 2 transactional Which read and write capacity cost-effectively meets these requirements?

<details>
<summary>Click to answer</summary>

- [x] Read 10; write 2   

</details>

0.   Read 10; write 2

1.   Read 30; write 40

2.   Use on-demand scaling

3.   Read 300; write 400


### A company wants to containerize an existing three-tier web application and deploy it to Amazon ECS Fargate. The application is using session data to keep track of user activities. Which approach would provide the BEST user experience?

<details>
<summary>Click to answer</summary>

- [x] Enable session stickiness in the existing Network Load Balancer and manage the session data in the container.   

</details>

0.   Provision a Redis cluster in Amazon ElastiCache and save the session data in the cluster.

1.   Create a session table in Amazon Redshift and save the session data in the database table.

2.   Enable session stickiness in the existing Network Load Balancer and manage the session data in the container.

3.   Use an Amazon S3 bucket as data store and save the session data in the bucket.


### An application is using a single-node Amazon ElastiCache for Redis instance to improve read performance. Over time, demand for the application has increased exponentially, which has increased the load on the ElastiCache instance. It is critical that this cache layer handles the load and is resilient in case of node failures. What can the Developer do to address the load and resiliency requirements?

<details>
<summary>Click to answer</summary>

- [x] Add a read replica instance.   

</details>

0.   Add a read replica instance.

1.   Migrate to a Memcached cluster.

2.   Migrate to an Amazon Elasticsearch Service cluster.

3.   Vertically scale the ElastiCache instance.


### A Developer is investigating an application's performance issues. The application consists of hundreds of microservices, and a single API call can potentially have a deep call stack. The Developer must isolate the component that is causing the issue. Which AWS service or feature should the Developer use to gather information about what is happening and isolate the fault?

<details>
<summary>Click to answer</summary>

- [x] AWS X-Ray.   

</details>

0.   AWS X-Ray.

1.   VPC Flow Logs.

2.   Amazon GuardDuty.

3.   Amazon Macie.


### A Company runs continuous integration/continuous delivery (CI/CD) pipelines for its application on AWS CodePipeline. A Developer must write unit tests and run them as part of the pipelines before staging the artifacts for testing. How should the Developer incorporate unit tests as part of CI/CD pipelines?

<details>
<summary>Click to answer</summary>

- [x] Create a testing branch in AWS CodeCommit to run unit tests.   

</details>

0.   Create a separate CodePipeline pipeline to run unit tests.

1.   Update the AWS CodeBuild specification to include a phase for running unit tests.

2.   Install the AWS CodeDeploy agent on an Amazon EC2 instance to run unit tests.

3.   Create a testing branch in AWS CodeCommit to run unit tests.


### An application has the following requirements: Performance efficiency of seconds with up to a minute of latency. The data storage size may grow up to thousands of terabytes. Per-message sizes may vary between 100 KB and 100 MB. Data can be stored as key/value stores supporting eventual consistency. What is the MOST cost-effective AWS service to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Amazon DynamoDB.   

</details>

0.   Amazon DynamoDB.

1.   Amazon S3.

2.   Amazon RDS (with a MySQL engine).

3.   Amazon ElastiCache.


### A Developer must allow guest users without logins to access an Amazon Cognito-enabled site to view files stored within an Amazon S3 bucket. How should the Developer meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Create a new user pool, disable authentication access, and grant access to AWS resources.   

</details>

0.   Create a blank user ID in a user pool, add to the user group, and grant access to AWS resources.

1.   Create a new identity pool, enable access to authenticated identities, and grant access to AWS resources.

2.   Create a new user pool, enable access to authenticated identifies, and grant access to AWS resources.

3.   Create a new user pool, disable authentication access, and grant access to AWS resources.


### A Developer has written code for an application and wants to share it with other Developers on the team to receive feedback. The shared application code needs to be stored long-term with multiple versions and batch change tracking. Which AWS service should the Developer use?

<details>
<summary>Click to answer</summary>

- [x] AWS CodeCommit.   

</details>

0.   AWS CodeBuild.

1.   Amazon S3.

2.   AWS CodeCommit.

3.   AWS Cloud9.


### A Developer has discovered that an application responsible for processing messages in an Amazon SQS queue is routinely falling behind. The application is capable of processing multiple messages in one execution, but is only receiving one message at a time. What should the Developer do to increase the number of messages the application receives?

<details>
<summary>Click to answer</summary>

- [x] Call the ReceiveMessage API to set MaxNumberOfMessages to a value greater than the default of 1.   

</details>

0.   Call the ChangeMessageVisibility API for the queue and set MaxNumberOfMessages to a value greater than the default of 1.

1.   Call the AddPermission API to set MaxNumberOfMessages for the ReceiveMessage action to a value greater than the default of 1.

2.   Call the ReceiveMessage API to set MaxNumberOfMessages to a value greater than the default of 1.

3.   Call the SetQueueAttributes API for the queue and set MaxNumberOfMessages to a value greater than the default of 1.


### A Developer registered an AWS Lambda function as a target for an Application Load Balancer (ALB) using a CLI command. However, the Lambda function is not being invoked when the client sends requests through the ALB. Why is the Lambda function not being invoked?

<details>
<summary>Click to answer</summary>

- [x] The permissions to invoke the Lambda function are missing.   

</details>

0.   A Lambda function cannot be registered as a target for an ALB.

1.   A Lambda function can be registered with an ALB using AWS Management Console only.

2.   The permissions to invoke the Lambda function are missing.

3.   Cross-zone is not enabled on the ALB.


### A company provides APIs as a service and commits to a service level agreement (SLA) with all its users. To comply with each SLA, what should the company do?

<details>
<summary>Click to answer</summary>

- [x] Enable default throttling limits for each stage after deploying the APIs.   

</details>

0.   Enable throttling limits for each method in Amazon API Gateway.

1.   Create a usage plan for each user and request API keys to access the APIs.

2.   Enable API rate limiting in Amazon Cognito for each user.

3.   Enable default throttling limits for each stage after deploying the APIs.


### A Developer is preparing a deployment package using AWS CloudFormation. The package consists of two separate templates: one for the infrastructure and one for the application. The application has to be inside the VPC that is created from the infrastructure template. How can the application stack refer to the VPC created from the infrastructure template?

<details>
<summary>Click to answer</summary>

- [x] Use the Ref function to import the VPC into the application stack from the infrastructure template.   

</details>

0.   Use the Ref function to import the VPC into the application stack from the infrastructure template.

1.   Use the export flag in the infrastructure template, and then use the Fn::ImportValue function in the application template.

2.   Use the DependsOn attribute to specify that the application instance depends on the VPC in the application template.

3.   Use the Fn::GetAtt function to include the attribute of the VPC in the application template.


### A Developer needs to create an application that supports Security Assertion Markup Language (SAML) and Facebook authentication. It must also allow access to AWS services, such as Amazon DynamoDB. Which AWS service or feature will meet these requirements with the LEAST amount of additional coding?

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito user pools.   

</details>

0.   AWS AppSync.

1.   Amazon Cognito identity pools.

2.   Amazon Cognito user pools.

3.   Amazon Lambda@Edge.


### A Developer is trying to monitor an application's status by running a cron job that returns 1 if the service is up and 0 if the service is down. The Developer created code that uses an AWS CLI put-metric-alarm command to publish the custom metrics to Amazon CloudWatch and create an alarm. However, the Developer is unable to create an alarm as the custom metrics do not appear in the CloudWatch console. What is causing this issue?

<details>
<summary>Click to answer</summary>

- [x] The Developer needs to use the put-metric-data command.   

</details>

0.   Sending custom metrics using the CLI is not supported.

1.   The Developer needs to use the put-metric-data command.

2.   The Developer must use a unified CloudWatch agent to publish custom metrics.

3.   The code is not running on an Amazon EC2 instance.


### A Developer has written an application that runs on Amazon EC2 instances and generates a value every minute. The Developer wants to monitor and graph the values generated over time without logging in to the instance each time. Which approach should the Developer use to achieve this goal?

<details>
<summary>Click to answer</summary>

- [x] Publish each generated value as a custom metric to Amazon CloudWatch using available AWS SDKs.   

</details>

0.   Use the Amazon CloudWatch metrics reported by default for all EC2 instances. View each value from the CloudWatch console.

1.   Develop the application to store each value in a file on Amazon S3 every minute with the timestamp as the name.

2.   Publish each generated value as a custom metric to Amazon CloudWatch using available AWS SDKs.

3.   Store each value as a variable and add the variable to the list of EC2 metrics that should be reported to the Amazon CloudWatch console.


### A Development team decides to adopt a continuous integration/continuous delivery (CI/CD) process using AWS CodePipeline and AWS CodeCommit for a new application. However, management wants a person to review and approve the code before it is deployed to production. How can the Development team add a manual approver to the CI/CD pipeline?

<details>
<summary>Click to answer</summary>

- [x] Add an approval action to the pipeline. Configure the approval action to publish to an Amazon SNS topic when approval is required. The pipeline execution will stop and wait for an approval.   

</details>

0.   Use AWS SES to send an email to approvers when their action is required. Develop a simple application that allows approvers to accept or reject a build. Invoke an AWS Lambda function to advance the pipeline when a build is accepted.

1.   If approved, add an approved tag when pushing changes to the CodeCommit repository. CodePipeline will proceed to build and deploy approved commits without interruption.

2.   Add an approval step to CodeCommit. Commits will not be saved until approved.

3.   Add an approval action to the pipeline. Configure the approval action to publish to an Amazon SNS topic when approval is required. The pipeline execution will stop and wait for an approval.


### A Developer is building a serverless application using AWS Lambda and must create a REST API using an HTTP GET method. What needs to be defined to meet this requirement? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] An Amazon API Gateway with a Lambda function.
- [x] An exposed GET method in an Amazon API Gateway.   

</details>

0.   A Lambda@Edge function.

1.   An Amazon API Gateway with a Lambda function.

2.   An exposed GET method in an Amazon API Gateway.

3.   An exposed GET method in the Lambda function.

4.   An exposed GET method in Amazon Route 53.


### A Developer is writing an application in AWS Lambda. To simplify testing and deployments, the Developer needs the database connection string to be easily changed without modifying the Lambda code. How can this requirement be met?

<details>
<summary>Click to answer</summary>

- [x] Store the connection string in AWS KMS.   

</details>

0.   Store the connection string as a secret in AWS Secrets Manager.

1.   Store the connection string in an IAM user account.

2.   Store the connection string in AWS KMS.

3.   Store the connection string as a Lambda layer.


### A company is launching an ecommerce website and will host the static data in Amazon S3. The company expects approximately 1,000 transactions per second (TPS) for GET and PUT requests in total. Logging must be enabled to track all requests and must be retained for auditing purposes. What is the MOST cost-effective solution?

<details>
<summary>Click to answer</summary>

- [x] Enable AWS CloudTrail logging for the S3 bucket-level action and create a lifecycle policy to expire the data in 90 days.   

</details>

0.   Enable AWS CloudTrail logging for the S3 bucket-level action and create a lifecycle policy to move the data from the log bucket to Amazon S3 Glacier in 90 days.

1.   Enable S3 server access logging and create a lifecycle policy to expire the data in 90 days.

2.   Enable AWS CloudTrail logging for the S3 bucket-level action and create a lifecycle policy to expire the data in 90 days.

3.   Enable S3 server access logging and create a lifecycle policy to move the data to Amazon S3 Glacier in 90 days.


### A Developer decides to store highly secure data in Amazon S3 and wants to implement server-side encryption (SSE) with granular control of who can access the master key. Company policy requires that the master key be created, rotated, and disabled easily when needed, all for security reasons. Which solution should be used to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] SSE with AWS Secrets Manager.   

</details>

0.   SSE with Amazon S3 managed keys (SSE-S3).

1.   SSE with AWS KMS managed keys (SSE-KMS).

2.   SSE with AWS Secrets Manager.

3.   SSE with customer-provided encryption keys.


### A Developer is migrating an on-premises application to AWS. The application currently takes user uploads and saves them to a local directory on the server. All uploads must be saved and made immediately available to all instances in an Auto Scaling group. Which approach will meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon EBS and file synchronization software to achieve eventual consistency among the Auto Scaling group.   

</details>

0.   Use Amazon EBS and configure the application AMI to use a snapshot of the same EBS instance on boot.

1.   Use Amazon S3 and rearchitect the application so all uploads are placed in S3.

2.   Use instance storage and share it between instances launched from the same Amazon Machine Image (AMI).

3.   Use Amazon EBS and file synchronization software to achieve eventual consistency among the Auto Scaling group.


### A Developer implemented a static website hosted in Amazon S3 that makes web service requests hosted in Amazon API Gateway and AWS Lambda. The site is showing an error that reads: 'No 'Access-Control-Allow-Origin' header is present on the requested resource. Origin 'null' is therefore not allowed access.' What should the Developer do to resolve this issue?

<details>
<summary>Click to answer</summary>

- [x] Enable cross-origin resource sharing (CORS) for the method in API Gateway.   

</details>

0.   Enable cross-origin resource sharing (CORS) on the S3 bucket.

1.   Enable cross-origin resource sharing (CORS) for the method in API Gateway.

2.   Add the Access-Control-Request-Method header to the request.

3.   Add the Access-Control-Request-Headers header to the request.


### A Developer is building an application that needs to store data in Amazon S3. Management requires that the data be encrypted before it is sent to Amazon S3 for storage. The encryption keys need to be managed by the Security team. Which approach should the Developer take to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Implement client-side encryption using an AWS KMS managed customer master key (CMK).   

</details>

0.   Implement server-side encryption using customer-provided encryption keys (SSE-C).

1.   Implement server-side encryption by using a client-side master key.

2.   Implement client-side encryption using an AWS KMS managed customer master key (CMK).

3.   Implement client-side encryption using Amazon S3 managed keys.


### A Developer has written an Amazon Kinesis Data Streams application. As usage grows and traffic increases over time, the application is regularly receiving ProvisionedThroughputExceededException error messages. Which steps should the Developer take to resolve the error? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Increase the number of shards in the data stream.
- [x] Specify a shard iterator using the ShardIterator parameter.   

</details>

0.   Use Auto Scaling to scale the stream for better performance.

1.   Increase the delay between the GetRecords call and the PutRecords call.

2.   Increase the number of shards in the data stream.

3.   Specify a shard iterator using the ShardIterator parameter.

4.   Implement exponential backoff on the GetRecords call and the PutRecords call.


### A Developer is publishing critical log data to a log group in Amazon CloudWatch Logs, which was created 2 months ago. The Developer must encrypt the log data using an AWS KMS customer master key (CMK) so future data can be encrypted to comply with the company's security policy. How can the Developer meet this requirement?

<details>
<summary>Click to answer</summary>

- [x] Use the AWS CLI associate-kms-key command and specify the key Amazon Resource Name (ARN)   

</details>

0.   Use the CloudWatch Logs console and enable the encrypt feature on the log group.

1.   Use the AWS CLI create-log-group command and specify the key Amazon Resource Name (ARN).

2.   Use the KMS console and associate the CMK with the log group.

3.   Use the AWS CLI associate-kms-key command and specify the key Amazon Resource Name (ARN)


### A Developer has code running on Amazon EC2 instances that needs read-only access to an Amazon DynamoDB table. What is the MOST secure approach the Developer should take to accomplish this task?

<details>
<summary>Click to answer</summary>

- [x] Use an IAM role with Administrator access applied to the EC2 instance.   

</details>

0.   Create a user access key for each EC2 instance with read-only access to DynamoDB. Place the keys in the code. Redeploy the code as keys rotate.

1.   Use an IAM role with an AmazonDynamoDBReadOnlyAccess policy applied to the EC2 instances.

2.   Run all code with only AWS account root user access keys to ensure maximum access to services.

3.   Use an IAM role with Administrator access applied to the EC2 instance.


### A Developer migrated a web application to AWS. As part of the migration, the Developer implemented an automated continuous integration/continuous improvement (CI/CD) process using a blue/green deployment. The deployment provisions new Amazon EC2 instances in an Auto Scaling group behind a new Application Load Balancer. After the migration was completed, the Developer began receiving complaints from users getting booted out of the system. The system also requires users to log in after every new deployment. How can these issues be resolved?

<details>
<summary>Click to answer</summary>

- [x] Turn on sticky sessions in the Application Load Balancer.   

</details>

0.   Use rolling updates instead of a blue/green deployment.

1.   Externalize the user sessions to Amazon ElastiCache.

2.   Turn on sticky sessions in the Application Load Balancer.

3.   Use multicast to replicate session information.


### A Developer wants to insert a record into an Amazon DynamoDB table as soon as a new file is added to an Amazon S3 bucket. Which set of steps would be necessary to achieve this?

<details>
<summary>Click to answer</summary>

- [x] Configure an S3 event to invoke a Lambda function that inserts records into DynamoDB.   

</details>

0.   Create an event with Amazon CloudWatch Events that will monitor the S3 bucket and then insert the records into DynamoDB.

1.   Configure an S3 event to invoke a Lambda function that inserts records into DynamoDB.

2.   Create a Lambda function that will poll the S3 bucket and then insert the records into DynamoDB.

3.   Create a cron job that will run at a scheduled time and insert the records into DynamoDB.


### A company has implemented AWS CodeDeploy as part of its cloud native CI/CD stack. The company enables automatic rollbacks while deploying a new version of a popular web application from in-place to Amazon EC2. What occurs if the deployment of the new version fails due to code regression?

<details>
<summary>Click to answer</summary>

- [x] CodeDeploy switches the Amazon Route 53 alias records back to the known good green deployment and terminates the failed blue deployment.   

</details>

0.   The last known good deployment is automatically restored using the snapshot stored in Amazon S3.

1.   CodeDeploy switches the Amazon Route 53 alias records back to the known good green deployment and terminates the failed blue deployment.

2.   A new deployment of the last known version of the application is deployed with a new deployment ID.

3.   AWS CodePipeline promotes the most recent deployment with a SUCCEEDED status to production.


### A Developer uses Amazon S3 buckets for static website hosting. The Developer creates one S3 bucket for the code and another S3 bucket for the assets, such as image and video files. Access is denied when a user attempts to access the assets bucket from the code bucket, with the website application showing a 403 error. How should the Developer solve this issue?

<details>
<summary>Click to answer</summary>

- [x] Edit the bucket policy of the assets bucket to open access to all principals.   

</details>

0.   Create an IAM role and apply it to the assets bucket for the code bucket to be granted access.

1.   Edit the bucket policy of the assets bucket to open access to all principals.

2.   Edit the bucket policy of the assets bucket to open access to all principals.

3.   Change the code bucket to use AWS Lambda functions instead of static website hosting.


### A company has implemented AWS CodePipeline to automate its release pipelines. The Development team is writing an AWS Lambda function what will send notifications for state changes of each of the actions in the stages. Which steps must be taken to associate the Lambda function with the event source?

<details>
<summary>Click to answer</summary>

- [x] Create an event trigger and specify the Lambda function from the CodePipeline console.   

</details>

0.   Create a trigger that invokes the Lambda function from the Lambda console by selecting CodePipeline as the event source.

1.   Create an event trigger and specify the Lambda function from the CodePipeline console.

2.   Create an Amazon CloudWatch alarm that monitors status changes in Code Pipeline and triggers the Lambda function.

3.   Create an Amazon CloudWatch Events rule that uses CodePipeline as an event source.


### A Developer has built an application running on AWS Lambda using AWS Serverless Application Model (AWS SAM). What is the correct order of execution to successfully deploy the application?

<details>
<summary>Click to answer</summary>

- [x] 1. Build the SAM template locally. 2. Package the SAM template onto Amazon S3. 3. Deploy the SAM template from Amazon S3.   

</details>

0.   1. Build the SAM template in Amazon EC2. 2. Package the SAM template to Amazon EBS storage. 3. Deploy the SAM template from Amazon EBS.

1.   1. Build the SAM template locally. 2. Package the SAM template onto Amazon S3. 3. Deploy the SAM template from Amazon S3.

2.   1. Build the SAM template locally. 2. Deploy the SAM template from Amazon S3. 3. Package the SAM template for use.

3.   1. Build the SAM template locally. 2. Package the SAM template from AWS CodeCommit. 3. Deploy the SAM template to CodeCommit.


### A company wants to migrate an imaging service to Amazon EC2 while following security best practices. The images are sourced and read from a non-public Amazon S3 bucket. What should a Developer do to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Create an IAM user with read-only permissions for the S3 bucket. Temporarily store the user credentials in the user data of the EC2 instance.   

</details>

0.   Create an IAM user with read-only permissions for the S3 bucket. Temporarily store the user credentials in the Amazon EBS volume of the EC2 instance.

1.   Create an IAM user with read-only permissions for the S3 bucket. Temporarily store the user credentials in the user data of the EC2 instance.

2.   Create an EC2 service role with read-only permissions for the S3 bucket. Attach the role to the EC2 instance.

3.   Create an S3 service role with read-only permissions for the S3 bucket. Attach the role to the EC2 instance.


### A Development team wants to immediately build and deploy an application whenever there is a change to the source code. Which approaches could be used to trigger the deployment? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Store the source code in an encrypted Amazon EBS volume. Configure AWS CodePipeline to start whenever a file in the volume changes.
- [x] Store the source code in an AWS CodeCommit repository. Configure AWS CodePipeline to start whenever a change is committed to the repository.   

</details>

0.   Store the source code in an Amazon S3 bucket. Configure AWS CodePipeline to start whenever a file in the bucket changes.

1.   Store the source code in an encrypted Amazon EBS volume. Configure AWS CodePipeline to start whenever a file in the volume changes.

2.   Store the source code in an AWS CodeCommit repository. Configure AWS CodePipeline to start whenever a change is committed to the repository.

3.   Store the source code in an Amazon S3 bucket. Configure AWS CodePipeline to start every 15 minutes.

4.   Store the source code in an Amazon EC2 instance's ephemeral storage. Configure the instance to start AWS CodePipeline whenever there are changes to the source code.


### An application ingests a large number of small messages and stores them in a database. The application uses AWS Lambda. A Development team is making changes to the application's processing logic. In testing, it is taking more than 15 minutes to process each message. The team is concerned the current backend may time out. Which changes should be made to the backend system to ensure each message is processed in the MOST scalable way?

<details>
<summary>Click to answer</summary>

- [x] Add the messages to an Amazon SQS queue. Set up Amazon EC2 instances in an Auto Scaling group to poll the queue and process the messages as they arrive.   

</details>

0.   Add the messages to an Amazon SQS queue. Set up and Amazon EC2 instance to poll the queue and process messages as they arrive.

1.   Add the messages to an Amazon SQS queue. Set up Amazon EC2 instances in an Auto Scaling group to poll the queue and process the messages as they arrive.

2.   Create a support ticket to increase the Lambda timeout to 60 minutes to allow for increased processing time.

3.   Change the application to directly insert the body of the message into an Amazon RDS database.


### A Software Engineer developed an AWS Lambda function in Node.js to do some CPU-intensive data processing. With the default settings, the Lambda function takes about 5 minutes to complete. Which approach should a Developer take to increase the speed of completion?

<details>
<summary>Click to answer</summary>

- [x] Increase the available memory to the function.   

</details>

0.   Instead of using Node.js, rewrite the Lambda function using Python.

1.   Instead of packaging the libraries in the ZIP file with the function, move them to a Lambda layer and use the layer with the function.

2.   Allocate the maximum available CPU units to the function.

3.   Increase the available memory to the function.


### An online retail company has deployed a serverless application with AWS Lambda, Amazon API Gateway, Amazon S3, and Amazon DynamoDB using AWS CloudFormation. The company rolled out a new release with major upgrades to the Lambda function and deployed the release to production. Subsequently, the application stopped working. Which solution should bring the application back up as quickly as possible?

<details>
<summary>Click to answer</summary>

- [x] Roll back the Lambda function to the previous version.   

</details>

0.   Redeploy the application on Amazon EC2 so the Lambda function can resolve dependencies.

1.   Migrate DynamoDB to Amazon RDS and redeploy the Lambda function.

2.   Roll back the Lambda function to the previous version.

3.   Deploy the latest Lambda function in a different Region.


### A Developer is writing an application that will run on Amazon EC2 instances in an Auto Scaling group. The Developer wants to externalize session state to support the application. Which services will meet these needs? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito.
- [x] Amazon EBS.   

</details>

0.   Amazon DynamoDB.

1.   Amazon Cognito.

2.   Amazon ElastiCache.

3.   Amazon EBS.

4.   Amazon SQS.


### A Developer has a legacy application that is hosted on-premises. Other applications hosted on AWS depend on the on-premises application for proper functioning. In case of any application errors, the Developer wants to be able to use Amazon CloudWatch to monitor and troubleshoot all applications from one place. How can the Developer accomplish this?

<details>
<summary>Click to answer</summary>

- [x] Download the CloudWatch agent to the on-premises server. Configure the agent to use IAM user credentials with permissions for CloudWatch.   

</details>

0.   Install an AWS SDK on the on-premises server to automatically send logs to CloudWatch.

1.   Download the CloudWatch agent to the on-premises server. Configure the agent to use IAM user credentials with permissions for CloudWatch.

2.   Upload log files from the on-premises server to Amazon S3 and have CloudWatch read the files.

3.   Upload log files from the on-premises server to an Amazon EC2 instance and have the instance forward the logs to CloudWatch.


### A company is developing an application that will be accessed through the Amazon API Gateway REST API. Registered users should be the only ones who can access certain resources of this API. The token being used should expire automatically and needs to be refreshed periodically. How can a Developer meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Create an Amazon Cognito user pool, configure the Cognito Authorizer in API Gateway, and use the identity or access token.   

</details>

0.   Create an Amazon Cognito identity pool, configure the Amazon Cognito Authorizer in API Gateway, and use the temporary credentials generated by the identity pool.

1.   Create and maintain a database record for each user with a corresponding token and use an AWS Lambda authorizer in API Gateway.

2.   Create an Amazon Cognito user pool, configure the Cognito Authorizer in API Gateway, and use the identity or access token.

3.   Create an IAM user for each API user, attach an invoke permissions policy to the API, and use an IAM authorizer in API Gateway.


### A Developer is working on a serverless project based in Java. Initial testing shows a cold start takes about 8 seconds on average for AWS Lambda functions. What should the Developer do to reduce the cold start time? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Add the Spring Framework to the project and enable dependency injection.
- [x] Change the Lambda invocation mode from synchronous to asynchronous.   

</details>

0.   Add the Spring Framework to the project and enable dependency injection.

1.   Reduce the deployment package by including only needed modules from the AWS SDK for Java.

2.   Increase the memory allocation setting for the Lambda function.

3.   Increase the timeout setting for the Lambda function.

4.   Change the Lambda invocation mode from synchronous to asynchronous.


### A Developer is leveraging a Border Gateway Protocol (BGP)-based AWS VPN connection to connect from on-premises to Amazon EC2 instances in the Developer's account. The Developer is able to access an EC2 instance in subnet A, but is unable to access an EC2 instance in subnet B in the same VPC. Which logs can the Developer use to verify whether the traffic is reaching subnet B?

<details>
<summary>Click to answer</summary>

- [x] VPC Flow Logs.   

</details>

0.   VPN logs.

1.   BGP logs

2.   VPC Flow Logs.

3.   AWS CloudTrail logs.


### A Developer has created a new AWS IAM user that has s3 putObject permission to write to a specific Amazon S3 bucket. This S3 bucket uses server-side encryption with AWS KMS managed keys (SSE-KMS) as the default encryption. Using the access key and secret key of the IAM user, the application received an access denied error when calling the PutObject API. How can this issue be resolved?

<details>
<summary>Click to answer</summary>

- [x] Update the policy of the IAM user to allow the kms:GenerateDataKey action.   

</details>

0.   Update the policy of the IAM user to allow the s3 Encrypt action.

1.   Update the bucket policy of the S3 bucket to allow the IAM user to upload objects.

2.   Update the policy of the IAM user to allow the kms:GenerateDataKey action.

3.   Update the ACL of the S3 bucket to allow the IAM user to upload objects.


### A company has a web application that uses an Amazon Cognito user pool for authentication. The company wants to create a login page with the company logo. What should a Developer do to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Upload the logo to the Amazon Cognito app settings and point to the logo on a custom login page.   

</details>

0.   Create a hosted user interface in Amazon Cognito and customize it with the company logo.

1.   Create a login page with the company logo and upload it to Amazon Cognito.

2.   Create a login page in Amazon API Gateway with the logo and save the link in Amazon Cognito.

3.   Upload the logo to the Amazon Cognito app settings and point to the logo on a custom login page.


### A Developer is working on an AWS Lambda function that accesses Amazon DynamoDB. The Lambda function must retrieve an item and update some of its attributes, or create the item if it does not exist. The Lambda function has access to the primary key. Which IAM permissions should the Developer request for the Lambda function to achieve this functionality?

<details>
<summary>Click to answer</summary>

- [x] dynamodb:UpdateItem dynamodb:GetItem dynamodb:PutItem.   

</details>

0.   dynamodb:DeleteItem dynamodb:GetItem dynamodb:PutItem.

1.   dynamodb:UpdateItem dynamodb:GetItem dynamodb:DescribeTable.

2.   dynamodb:GetRecords dynamodb:PutItem dynamodb:UpdateTable.

3.   dynamodb:UpdateItem dynamodb:GetItem dynamodb:PutItem.


### A Developer is storing sensitive data generated by an application in Amazon S3. The Developer wants to encrypt the data at rest. A company policy requires an audit trail of when the master key was used and by whom. Which encryption option will meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Server-side encryption with AWS KMS managed keys (SSE-KMS).   

</details>

0.   Server-side encryption with Amazon S3 managed keys (SSE-S3).

1.   Server-side encryption with AWS KMS managed keys (SSE-KMS).

2.   Server-side encryption with customer-provided keys (SSE-C).

3.   Server-side encryption with self-managed keys.


### A company's website runs on an Amazon EC2 instance and uses Auto Scaling to scale the environment during peak times. Website users across the world are experiencing high latency due to static content on the EC2 instance, even during non-peak hours. Which combination of steps will resolve the latency issue? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Scale vertically by resizing the EC2 instances.
- [x] Store the application's static content in Amazon S3.   

</details>

0.   Double the Auto Scaling group's maximum number of servers.

1.   Host the application code on AWS Lambda.

2.   Scale vertically by resizing the EC2 instances.

3.   Create an Amazon CloudFront distribution to cache the static content.

4.   Store the application's static content in Amazon S3.


### A company is developing a web application that allows its employees to upload a profile picture to a private Amazon S3 bucket. There is no size limit for the profile pictures, which should be displayed every time an employee logs in. For security reasons, the pictures cannot be publicly accessible. What is a viable long-term solution for this scenario?

<details>
<summary>Click to answer</summary>

- [x] Save the picture's S3 key in an Amazon DynamoDB table. Create an Amazon S3 VPC endpoint to allow the employees to download pictures once they log in.   

</details>

0.   Generate a presigned URL when a picture is uploaded. Save the URL in an Amazon DynamoDB table. Return the URL to the browser when the employee logs in.

1.   Save the picture's S3 key in an Amazon DynamoDB table. Create an Amazon S3 VPC endpoint to allow the employees to download pictures once they log in.

2.   Encode a picture using base64. Save the base64 string in an Amazon DB table. Allow the browser to retrieve the string and convert it to a picture.

3.   Save the picture's S3 key in an Amazon DynamoDB table. Use a function to generate a presigned URL every time an employee logs in. Return the URL to the browser.


### A Developer is going to deploy an AWS Lambda function that requires significant CPU utilization. Which approach will MINIMIZE the average runtime of the function?

<details>
<summary>Click to answer</summary>

- [x] Deploy the function using Lambda layers.   

</details>

0.   Deploy the function into multiple AWS Regions.

1.   Deploy the function into multiple Availability Zones.

2.   Deploy the function using Lambda layers.

3.   Deploy the function with its memory allocation set to the maximum amount.


### A company has a legacy application that was migrated to a fleet of Amazon EC2 instances. The application stores data in a MySQL database that is currently installed on a single EC2 instance. The company has decided to migrate the database from the EC2 instance to MySQL on Amazon RDS. What should the Developer do to update the application to support data storage in Amazon RDS?

<details>
<summary>Click to answer</summary>

- [x] Update the database connection parameters in the application to point to the new RDS instance.   

</details>

0.   Update the database connection parameters in the application to point to the new RDS instance.

1.   Add a script to the EC2 instance that implements an AWS SDK for requesting database credentials.

2.   Create a new EC2 instance with an IAM role that allows access to the new RDS database.

3.   Create an AWS Lambda function that will route traffic, from the EC2 instance to the RDS database.


### A Developer has an e-commerce API hosted on Amazon ECS. Variable and spiking demand on the application is causing order processing to take too long. The application processes Amazon SQS queues. The ApproximateNumberOfMessagesVisible metric spikes at very high values throughout the day, which cause Amazon CloudWatch alarm breaches. Other ECS metrics for the API containers are well within limits. What can the Developer implement to improve performance while keeping costs low?

<details>
<summary>Click to answer</summary>

- [x] Step scaling policy.   

</details>

0.   Target tracking scaling policy.

1.   Docker Swarm.

2.   Service scheduler.

3.   Step scaling policy.


### A Developer wants to build an application that will allow new users to register and create new user accounts. The application must also allow users with social media accounts to log in using their social media credentials. Which AWS service or feature can be used to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito user pools.   

</details>

0.   AWS IAM.

1.   Amazon Cognito identity pools.

2.   Amazon Cognito user pools.

3.   AWS Directory Service.


### A company wants to implement authentication for its new REST service using Amazon API Gateway. To authenticate the calls, each request must include HTTP headers with a client ID and user ID. These credentials must be compared to authentication data in an Amazon DynamoDB table. What MUST the company do to implement this authentication in API Gateway?

<details>
<summary>Click to answer</summary>

- [x] Implement an Amazon Cognito authorizer that references the DynamoDB authentication table.   

</details>

0.   Implement an AWS Lambda authorizer that references the DynamoDB authentication table.

1.   Create a model that requires the credentials, then grant API Gateway access to the authentication table.

2.   Modify the integration requests to require the credentials, then grant API Gateway access to the authentication table.

3.   Implement an Amazon Cognito authorizer that references the DynamoDB authentication table.


### A Developer is trying to make API calls using SDK. The IAM user credentials used by the application require multi-factor authentication for all API calls. Which method the Developer use to access the multi-factor authentication protected API?

<details>
<summary>Click to answer</summary>

- [x] GetSessionToken.   

</details>

0.   GetFederationToken.

1.   GetCallerIdentity.

2.   GetSessionToken.

3.   DecodeAutherizationMessage.


### An application is running on a cluster of Amazon EC2 instances. While trying to read objects stored within a single Amazon S3 bucket that are encrypted with server-side encryption with AWS KMS managed keys (SSE-KMS), the application receives the following error. Which combination of steps should be taken to prevent this failure? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Contact AWS Support to request a S3 rate limit increase.
- [x] Import a customer master key (CMK) with a larger key size.   

</details>

0.   Contact AWS Support to request an AWS KMS rate limit increase.

1.   Perform error retries with exponential backoff in the application code.

2.   Contact AWS Support to request a S3 rate limit increase.

3.   Import a customer master key (CMK) with a larger key size.

4.   Use more than one customer master key (CMK) to encrypt S3 data.


### When developing an AWS Lambda function that processes Amazon Kinesis Data Streams, Administrators within the company must receive a notice that includes the processed data. How should the Developer write the function to send processed data to the Administrators?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon CloudWatch Events to send the processed data.   

</details>

0.   Separate the Lambda handler from the core logic.

1.   Use Amazon CloudWatch Events to send the processed data.

2.   Publish the processed data to an Amazon SNS topic.

3.   Push the processed data to Amazon SQS.


### A Developer is storing sensitive documents in Amazon S3 that will require encryption at rest. The encryption keys must be rotated annually, at least. What is the easiest way to achieve this?

<details>
<summary>Click to answer</summary>

- [x] Import a custom key into AWS KMS with annual rotation enabled.   

</details>

0.   Encrypt the data before sending it to Amazon S3.

1.   Import a custom key into AWS KMS with annual rotation enabled.

2.   Use AWS KMS with automatic key rotation.

3.   Export a key from AWS KMS to encrypt the data.


### A company is creating a REST service using an Amazon API Gateway with AWS Lambda integration. The service must run different versions for testing purposes. What would be the BEST way to accomplish this?

<details>
<summary>Click to answer</summary>

- [x] Create an API Gateway resource policy to isolate versions and provide context to the Lambda function(s).   

</details>

0.   Use an x-Version header to denote which version is being called and pass that header to the Lambda function(s).

1.   Create an API Gateway Lambda authorizer to route API clients to the correct API version.

2.   Create an API Gateway resource policy to isolate versions and provide context to the Lambda function(s).

3.   Deploy the API versions as unique stages with unique endpoints and use stage variables to provide further context.


### A Developer must encrypt a 100-GB object using AWS KMS. What is the BEST approach?

<details>
<summary>Click to answer</summary>

- [x] Make an GenerateDataKeyWithoutPlaintext API call that returns an encrypted copy of a data key. Use an encrypted key to encrypt the data.   

</details>

0.   Make an Encrypt API call to encrypt the plaintext data as ciphertext using a customer master key (CMK).

1.   Make an Encrypt API call to encrypt the plaintext data as ciphertext using a customer master key (CMK) with imported key material.

2.   Make an GenerateDataKey API call that returns a plaintext key and an encrypted copy of a data key. Use a plaintext key to encrypt the data.

3.   Make an GenerateDataKeyWithoutPlaintext API call that returns an encrypted copy of a data key. Use an encrypted key to encrypt the data.


### A Development team would like to migrate their existing application code from a GitHub repository to AWS CodeCommit. What needs to be created before they can migrate a cloned repository to CodeCommit over HTTPS?

<details>
<summary>Click to answer</summary>

- [x] A set of Git credentials generated from IAM.   

</details>

0.   A GitHub secure authentication token.

1.   A public and private SSH key file.

2.   A set of Git credentials generated from IAM.

3.   An Amazon EC2 IAM role with CodeCommit permissions.


### What item operation allows the retrieval of multiple items from a DynamoDB table in a single API call?

<details>
<summary>Click to answer</summary>

- [x] BatchGetltem.   

</details>

0.   Getltem.

1.   BatchGetltem.

2.   GetMultipleltems.

3.   GetltemRange.


### After launching an instance that you intend to serve as a NAT (Network Address Translation) device in a public subnet you modify your route tables to have the NAT device be the target of internet bound traffic of your private subnet. When you try and make an outbound connection to the Internet from an instance in the private subnet, you are not successful. NAT device be the target of internet bound traffic of your private subnet. Which of the following steps could resolve the issue?

<details>
<summary>Click to answer</summary>

- [x] Disabling the Source/Destination Check attribute on the NAT instance.   

</details>

0.   Attaching a second Elastic Network interface (ENI) to the NAT instance, and placing it in the private subnet.

1.   Attaching a second Elastic Network Interface (ENI) to the instance in the private subnet, and placing it in the public subnet.

2.   Disabling the Source/Destination Check attribute on the NAT instance.

3.   Attaching an Elastic IP address to the instance in the private subnet.


### You attempt to store an object in the US-STANDARD region in Amazon S3, and receive a confirmation that it has been successfully stored. You then immediately make another API call and attempt to read this object. S3 tells you that the object does not exist. What could explain this behavior?

<details>
<summary>Click to answer</summary>

- [x] US-STANDARD uses eventual consistency and it can take time for an object to be readable in a bucket.   

</details>

0.   US-STANDARD uses eventual consistency and it can take time for an object to be readable in a bucket.

1.   Objects in Amazon S3 do not become visible until they are replicated to a second region.

2.   US-STANDARD imposes a 1 second delay before new objects are readable.

3.   ou exceeded the bucket object limit, and once this limit is raised the object will be visible.


### What is the maximum number of S3 Buckets available per AWS account?

<details>
<summary>Click to answer</summary>

- [x] 100 per region.   

</details>

0.   100 per region.

1.   there is no limit.

2.   100 per account.

3.   500 per account.

4.   100 per IAM user.


### Which of the following items are required to allow an application deployed on an EC2 instance to write data to a DynamoDB table? Assume that no security Keys are allowed to be stored on the EC2 instance. (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Launch an EC2 Instance with the IAM Role included in the launch configuration.
- [x] Create an IAM Role that allows write access to the DynamoDB table.   

</details>

0.   Create an IAM User that allows write access to the DynamoDB table.

1.   Add an IAM Role to a running EC2 instance.

2.   Add an IAM User to a running EC2 Instance.

3.   Launch an EC2 Instance with the IAM Role included in the launch configuration.

4.   Create an IAM Role that allows write access to the DynamoDB table.

5.   Launch an EC2 Instance with the IAM User included in the launch configuration.


### Which of the following are correct statements with policy evaluation logic in AWS Identity and Access Management? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] By default, all requests are denied.
- [x] An explicit allow overrides default deny.   

</details>

0.   By default, all requests are denied.

1.   An explicit allow overrides an explicit deny.

2.   An explicit allow overrides default deny.

3.   An explicit deny does not override an explicit allow.

4.   By default, all request are allowed.


### You have an environment that consists of a public subnet using Amazon VPC and 3 instances that are running in this subnet. These three instances can successfully communicate with other hosts on the Internet. You launch a fourth instance in the same subnet, using the same AMI and security group configuration you used for the others, but find that this instance cannot be accessed from the Internet. What should you do to enable internet access?

<details>
<summary>Click to answer</summary>

- [x] Assign an Elastic IP address to the fourth instance.   

</details>

0.   Deploy a NAT instance into the public subnet.

1.   Modify the routing table for the public subnet.

2.   Configure a publically routable IP Address In the host OS of the fourth instance.

3.   Assign an Elastic IP address to the fourth instance.


### If a message is retrieved from a queue in Amazon SQS, how long is the message inaccessible to other users by default?

<details>
<summary>Click to answer</summary>

- [x] 30 seconds.   

</details>

0.   0 seconds.

1.   1 hour.

2.   1 day.

3.   forever.

4.   30 seconds.


### What is the format of structured notification messages sent by Amazon SNS?

<details>
<summary>Click to answer</summary>

- [x] An JSON object containing Messageld, unsubscribeURL, Subject, Message and other values.   

</details>

0.   An XML object containing Messageld, UnsubscribeURL, Subject, Message and other values.

1.   An JSON object containing Messageld, DuplicateFlag, Message and other values.

2.   An XML object containing Messageld, DuplicateFlag, Message and other values.

3.   An JSON object containing Messageld, unsubscribeURL, Subject, Message and other values.


### When uploading an object, what request header can be explicitly specified in a request to Amazon S3 to encrypt object data when saved on the server side?

<details>
<summary>Click to answer</summary>

- [x] x-amz-server-side-encryption.   

</details>

0.   x-amz-storage-class.

1.   Content-MD5.

2.   x-amz-security-token.

3.   x-amz-server-side-encryption.


### Which of the following platforms are supported by Elastic Beanstalk? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Apache Tomcat
- [x] .NET   

</details>

0.   Apache Tomcat

1.   .NET

2.   IBM Websphere

3.   Oracle JBoss

4.   Jetty


### Which code snippet below returns the URL of a load balanced web site created in CloudFormation with an AWS::ElasticLoadBalancing::LoadBalancer resource name 'ElasticLoad Balancer'?

<details>
<summary>Click to answer</summary>

- [x] "Fn::Join":[ "".["http://", {Fn::GetAtr": [ "ElasticLoadBalancer","DNSName"]}]].   

</details>

0.   "Fn::Join":[ "".["http://", {Fn::GetAtr": [ "ElasticLoadBalancer","DNSName"]}]].

1.   "Fn::Join":[ "".["http://", {Fn::GetAtr": [ "ElasticLoadBalancer","Url"]}]].

2.   "Fn::Join":[ "".["http://", {"Ref : "ElasticLoadBalancerUrl"}]].

3.   "Fn::Join":[ "".["http://", {"Ref : "ElasticLoadBalancer","DNSName"}]].


### Which features can be used to restrict access to data in S3? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Set an S3 Bucket policy.
- [x] Set an S3 ACL on the bucket or the object.   

</details>

0.   Use S3 Virtual Hosting.

1.   Set an S3 Bucket policy.

2.   Enable IAM Identity Federation.

3.   Set an S3 ACL on the bucket or the object.

4.   Create a CloudFront distribution for the bucket.


### What happens, by default, when one of the resources in a CloudFormation stack cannot be created?

<details>
<summary>Click to answer</summary>

- [x] Previously-created resources are deleted and the stack creation terminates.   

</details>

0.   Previously-created resources are kept but the stack creation terminates.

1.   Previously-created resources are deleted and the stack creation terminates.

2.   The stack creation continues, and the final results indicate which steps failed.

3.   CloudFormation templates are parsed in advance so stack creation is guaranteed to succeed.


### Which of the following are valid arguments for an SNS Publish request? (Choose THREE)

<details>
<summary>Click to answer</summary>

- [x] Subject.
- [x] Destination.
- [x] Message.   

</details>

0.   TopicAm.

1.   Subject.

2.   Destination.

3.   Format.

4.   Message.

5.   Language.


### How can software determine the public and private IP addresses of the Amazon EC2 instance that it is running on?

<details>
<summary>Click to answer</summary>

- [x] Query the local instance metadata.   

</details>

0.   Query the appropriate Amazon CloudWatch metric.

1.   Use ipconfig or ifconfig command.

2.   Query the local instance userdata.

3.   Query the local instance metadata.


### EC2 instances are launched from Amazon Machine images (AMIs). A given public AMI can:

<details>
<summary>Click to answer</summary>

- [x] Only be used to launch EC2 instances in the same AWS region as the AMI is stored.   

</details>

0.   Be used to launch EC2 Instances in any AWS region.

1.   Only be used to launch EC2 instances in the same country as the AMI is stored.

2.   Only be used to launch EC2 instances in the same AWS region as the AMI is stored.

3.   Only be used to launch EC2 instances in the same AWS availability zone as the AMI is stored


### Which EC2 API call would you use to retrieve a list of Amazon Machine Images (AMIs)?

<details>
<summary>Click to answer</summary>

- [x] DescribeImages.   

</details>

0.   DescribeInstances.

1.   DescribeAMIs.

2.   DescribeImages.

3.   GetAMIs.

4.   You cannot retrieve a list of AMIs as there are over 10,000 AMIs.


### In AWS, which security aspects are the customer's responsibility? (Choose FOUR)

<details>
<summary>Click to answer</summary>

- [x] Life-cycle management of IAM credentials.
- [x] Security Group and ACL (Access Control List) settings.
- [x] Encryption of EBS (Elastic Block Storage) volumes.
- [x] Patch management on the EC2 instance's operating system.   

</details>

0.   Life-cycle management of IAM credentials.

1.   Decommissioning storage devices.

2.   Security Group and ACL (Access Control List) settings.

3.   Encryption of EBS (Elastic Block Storage) volumes.

4.   Controlling physical access to compute resources.

5.   Patch management on the EC2 instance's operating system.


### When using a large Scan operation in DynamoDB, what technique can be used to minimize the impact of a scan on a table's provisioned throughput?

<details>
<summary>Click to answer</summary>

- [x] Define a range index on the table.   

</details>

0.   Set a smaller page size for the scan.

1.   Use parallel scans.

2.   Define a range index on the table.

3.   Prewarm the table by updating all items.


### How can you secure data at rest on an EBS volume?

<details>
<summary>Click to answer</summary>

- [x] Use an encrypted file system on top of the BBS volume.   

</details>

0.   Attach the volume to an instance using EC2's SSL interface.

1.   Write the data randomly instead of sequentially.

2.   Use an encrypted file system on top of the BBS volume.

3.   Encrypt the volume using the S3 server-side encryption service.

4.   Encrypt the volume using the S3 server-side encryption service.


### Which of the following is chosen as the default region when making an API call with an AWS SDK?

<details>
<summary>Click to answer</summary>

- [x] us-east-1.   

</details>

0.   ap-northeast-1.

1.   us-west-2.

2.   us-east-1.

3.   eu-west-1.

4.   us-central-1.


### Which of the following statements about SWF are true? (Choose THREE)

<details>
<summary>Click to answer</summary>

- [x] SWF tasks are assigned once and never duplicated.
- [x] SWF workflow executions can last up to a year.
- [x] SWF uses deciders and workers to complete tasks.   

</details>

0.   SWF tasks are assigned once and never duplicated.

1.   SWF requires an S3 bucket for workflow storage.

2.   SWF workflow executions can last up to a year.

3.   SWF triggers SNS notifications on task assignment.

4.   SWF uses deciders and workers to complete tasks.

5.   SWF requires at least 1 EC2 instance per domain.


### A startup s photo-sharing site is deployed in a VPC. An ELB distributes web traffic across two subnets. ELB session stickiness is configured to use the AWSgenerated session cookie, with a session TTL of 5 minutes. The webserver Auto Scaling Group is configured as: min-size=4, max-size=4, The startups preparing for a public launch, by running load-testing software installed on a single EC2 instance running in us-west-2 After 60 minutes of load-testing, the webserver logs show: Which recommendations can help ensure load-testing HTTP requests are evenly distributed across the four webservers? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Re-configure the load-testing software to re-resolve DNS for each web request.
- [x] Configure ELB and Auto Scaling to distribute across us-west-2a and us-west-2c.   

</details>

0.   Launch and run the load-tester EC2 instance from us-east-1 instead.

1.   Re-configure the load-testing software to re-resolve DNS for each web request.

2.   Use a 3rd-party load-testing service which offers globally-distributed test clients.

3.   Configure ELB and Auto Scaling to distribute across us-west-2a and us-west-2c.

4.   Configure ELB session stickiness to use the app-specific session cookie.


### Which of the following are valid SNS delivery transports? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] HTTP.
- [x] SMS.   

</details>

0.   HTTP.

1.   UDP.

2.   SMS.

3.   DynamoDB.

4.   Named Pipes.


### Company C has recently launched an online commerce site for bicycles on AWS. They have a 'Product' DynamoDB table that stores details for each bicycle, such as, manufacturer, color, price, quantity and size to display in the online store. Due to customer demand, they want to include an image for each bicycle along with the existing details. Which approach below provides the least impact to provisioned throughput on the 'Product' table?

<details>
<summary>Click to answer</summary>

- [x] Store the images in Amazon S3 and add an S3 URL pointer to the 'Product' table item for each image.   

</details>

0.   Serialize the image and store it in multiple DynamoDB tables.

1.   Create an 'Images' DynamoDB table to store the Image with a foreign key constraint to the 'Product' table.

2.   Add an image data type to the 'Product' table to store the images in binary format.

3.   Store the images in Amazon S3 and add an S3 URL pointer to the 'Product' table item for each image.


### Which DynamoDB limits can be raised by contacting AWS support? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] The number of tables per account.
- [x] The number of provisioned throughput units per account.   

</details>

0.   The number of hash keys per account.

1.   The maximum storage used per account.

2.   The number of tables per account.

3.   The number of local secondary indexes per account.

4.   The number of provisioned throughput units per account.


### When a Simple Queue Service message triggers a task that takes 5 minutes to complete, which process below will result in successful processing of the message and remove it from the queue while minimizing the chances of duplicate processing?

<details>
<summary>Click to answer</summary>

- [x] Retrieve the message with an increased visibility timeout, process the message, delete the message from the queue.   

</details>

0.   Retrieve the message with an increased visibility timeout, process the message, delete the message from the queue.

1.   Retrieve the message with an increased visibility timeout, delete the message from the queue, process the message.

2.   Retrieve the message with increased DelaySeconds, process the message, delete the message from the queue.

3.   Retrieve the message with increased DelaySeconds, delete the message from the queue, process the message.


### Company A has an S3 bucket containing premier content that they intend to make available to only paid subscribers of their website. The S3 bucket currently has default permissions of all objects being private to prevent inadvertent exposure of the premier content to non-paying website visitors. How can Company A provide only paid subscribers the ability to download a premier content file in the S3 bucket?

<details>
<summary>Click to answer</summary>

- [x] Generate a pre-signed object URL for the premier content file when a paid subscriber requests a download.   

</details>

0.   Apply a bucket policy that grants anonymous users to download the content from the S3 bucket.

1.   Generate a pre-signed object URL for the premier content file when a paid subscriber requests a download.

2.   Add a bucket policy that requires Multi-Factor Authentication for requests to access the S3 bucket objects.

3.   Enable server side encryption on the S3 bucket for data protection against the non-paying website visitors.


### Which of the following is an example of a good DynamoDB hash key schema for provisioned throughput efficiency?

<details>
<summary>Click to answer</summary>

- [x] User ID, where the application has many different users.   

</details>

0.   User ID, where the application has many different users.

1.   Status Code where most status codes are the same.

2.   Device ID, where one is by far more popular than all the others.

3.   Game Type, where there are three possible game types.


### An application stores payroll information nightly in DynamoDB for a large number of employees across hundreds of offices. Item attributes consist of individual name, office identifier, and cumulative daily hours. Managers run reports for ranges of names working in their office. One query is. 'Return all Items in this office for names starting with A through E'. Which table configuration will result in the lowest impact on provisioned throughput for this query?

<details>
<summary>Click to answer</summary>

- [x] Configure the table to have a range index on the name attribute, and a hash index on the office identifier.   

</details>

0.   Configure the table to have a hash index on the name attribute, and a range index on the office identifier.

1.   Configure the table to have a range index on the name attribute, and a hash index on the office identifier.

2.   Configure a hash index on the name attribute and no range index.

3.   Configure a hash index on the office Identifier attribute and no range index.


### What is one key difference between an Amazon EBS-backed and an instance-store backed instance?

<details>
<summary>Click to answer</summary>

- [x] Amazon EBS-backed instances can be stopped and restarted.   

</details>

0.   Virtual Private Cloud requires EBS backed instances.

1.   Amazon EBS-backed instances can be stopped and restarted.

2.   Auto scaling requires using Amazon EBS-backed instances.

3.   Instance-store backed instances can be stopped and restarted.


### Which of the following services are included at no additional cost with the use of the AWS platform?

<details>
<summary>Click to answer</summary>

- [x] Auto Scaling.
- [x] CloudFormation.   

</details>

0.   Simple Storage Service.

1.   Elastic Compute Cloud.

2.   Auto Scaling.

3.   Elastic Load Balancing.

4.   CloudFormation.

5.   Simple Workflow Service.


### Your application is trying to upload a 6 GB file to Simple Storage Service and receive a 'Your proposed upload exceeds the maximum allowed object size- error message. What is a possible solution for this?

<details>
<summary>Click to answer</summary>

- [x] Use the multi-part upload API for this object.   

</details>

0.   None, Simple Storage Service objects are limited to 5 GB.

1.   Use the multi-part upload API for this object.

2.   Use the large object upload API for this object.

3.   Contact support to increase your object size limit.

4.   Upload to a different region.


### What AWS products and features can be deployed by Elastic Beanstalk? (Choose THREE)

<details>
<summary>Click to answer</summary>

- [x] Auto scaling groups.
- [x] Elastic Load Balancers.
- [x] RDS Instances.   

</details>

0.   Auto scaling groups.

1.   Route 53 hosted zones.

2.   Elastic Load Balancers.

3.   RDS Instances.

4.   Elastic IP addresses.

5.   SQS Queues.


### Games-R-Us is launching a new game app for mobile devices. Users will log into the game using their existing Facebook account and the game will record player data and scoring information directly to a DynamoDB table. What is the most secure approach for signing requests to the DynamoDB API?

<details>
<summary>Click to answer</summary>

- [x] Request temporary security credentials using web identity federation to sign the requests.   

</details>

0.   Create an IAM user with access credentials that are distributed with the mobile app to sign the requests.

1.   Distribute the AWS root account access credentials with the mobile app to sign the requests.

2.   Request temporary security credentials using web identity federation to sign the requests.

3.   Establish cross account access between the mobile app and the DynamoDB table to sign the requests


### Which of the following programming languages have an officially supported AWS SDK? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] PHP.
- [x] Java.   

</details>

0.   Perl.

1.   PHP.

2.   Pascal.

3.   Java.

4.   SQL.


### A meteorological system monitors 600 temperature gauges, obtaining temperature samples every minute and saving each sample to a DynamoDB table Each sample involves writing 1K of data and the writes are evenly distributed over time. How much write throughput is required for the target table?

<details>
<summary>Click to answer</summary>

- [x] 10 write capacity units.   

</details>

0.   1 write capacity unit.

1.   10 write capacity units.

2.   60 write capacity units.

3.   600 write capacity units.

4.   3600 write capacity units.


### In DynamoDB, what type of HTTP response codes indicate that a problem was found with the client request sent to the service?

<details>
<summary>Click to answer</summary>

- [x] 4xx HTTP response code.   

</details>

0.   5xx HTTP response code.

1.   200 HTTP response code.

2.   306 HTTP response code.

3.   4xx HTTP response code.


### Company B provides an online image recognition service and utilizes SQS to decouple system components for scalability The SQS consumers poll the imaging queue as often as possible to keep end-to-end throughput as high as possible. However, Company B is realizing that polling in tight loops is burning CPU cycles and increasing costs with empty responses. How can Company B reduce the number of empty responses?

<details>
<summary>Click to answer</summary>

- [x] Set the Imaging queue ReceiveMessageWaitTimeSeconds attribute to 20 seconds.   

</details>

0.   Set the imaging queue visibility Timeout attribute to 20 seconds.

1.   Set the Imaging queue ReceiveMessageWaitTimeSeconds attribute to 20 seconds.

2.   Set the imaging queue MessageRetentionPeriod attribute to 20 seconds.

3.   Set the DelaySeconds parameter of a message to 20 seconds.


### An Amazon S3 bucket, 'myawsbucket' is configured with website hosting in Tokyo region, what is the region-specific website endpoint?

<details>
<summary>Click to answer</summary>

- [x] myawsbucket.s3-website-ap-northeast-1.amazonaws.com   

</details>

0.   www.myawsbucket.ap-northeast-1.amazonaws.com

1.   myawsbucket.s3-website-ap-northeast-1.amazonaws.com

2.   myawsbucket.amazonaws.com

3.   myawsbucket.tokyo.amazonaws.com


### You are inserting 1000 new items every second in a DynamoDB table. Once an hour these items are analyzed and then are no longer needed. You need to minimize provisioned throughput, storage, and API calls. Given these requirements, what is the most efficient way to manage these Items after the analysis?

<details>
<summary>Click to answer</summary>

- [x] Delete the table and create a new table per hour.   

</details>

0.   Retain the items in a single table.

1.   Delete items individually over a 24 hour period.

2.   Delete the table and create a new table per hour.

3.   Create a new table per hour.


### You have written an application that uses the Elastic Load Balancing service to spread traffic to several web servers. Your users complain that they are sometimes forced to login again in the middle of using your application, after they have already logged in. This is not behavior you have designed. What is a possible solution to prevent this happening?

<details>
<summary>Click to answer</summary>

- [x] Use ElastiCache to save session state.   

</details>

0.   Use instance memory to save session state.

1.   Use instance storage to save session state.

2.   Use EBS to save session state.

3.   Use ElastiCache to save session state.

4.   Use Glacier to save session slate.


### You run an ad-supported photo sharing website using S3 to serve photos to visitors of your site. At some point you find out that other sites have been linking to the photos on your site, causing loss to your business. What is an effective method to mitigate this?

<details>
<summary>Click to answer</summary>

- [x] Remove public read access and use signed URLs with expiry dates.   

</details>

0.   Store photos on an EBS volume of the web server.

1.   Remove public read access and use signed URLs with expiry dates.

2.   Use CloudFront distributions for static content.

3.   Block the IPs of the offending websites in Security Groups.


### Which statements about DynamoDB are true? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] DynamoDB uses optimistic concurrency control.
- [x] DynamoDB uses conditional writes for consistency.   

</details>

0.   DynamoDB uses a pessimistic locking model.

1.   DynamoDB uses optimistic concurrency control.

2.   DynamoDB uses conditional writes for consistency.

3.   DynamoDB restricts item access during reads.

4.   DynamoDB restricts item access during writes.


### You are providing AWS consulting services for a company developing a new mobile application that will be leveraging Amazon SNS Mobile Push for push notifications. In order to send direct notification messages to individual devices each device registration identifier or token needs to be registered with SNS; however the developers are not sure of the best way to do this. You advise them to:

<details>
<summary>Click to answer</summary>

- [x] Call the CreatePlatformEndPoint API function to register multiple device tokens.   

</details>

0.   Bulk upload the device tokens contained in a CSV file via the AWS Management Console.

1.   Let the push notification service (e.g. Amazon Device Messaging) handle the registration.

2.   Implement a token vending service to handle the registration.

3.   Call the CreatePlatformEndPoint API function to register multiple device tokens.


### You are writing to a DynamoDB table and receive the following exception: 'ProvisionedThroughputExceededException'. though according to your Cloudwatch metrics for the table, you are not exceeding your provisioned throughput. What could be an explanation for this?

<details>
<summary>Click to answer</summary>

- [x] You're exceeding your capacity on a particular Hash Key.   

</details>

0.   You haven't provisioned enough DynamoDB storage instances.

1.   You're exceeding your capacity on a particular Range Key.

2.   You're exceeding your capacity on a particular Hash Key.

3.   You're exceeding your capacity on a particular Sort Key.

4.   You haven't configured DynamoDB Auto Scaling triggers.


### If an application is storing hourly log files from thousands of instances from a high traffic web site, which naming scheme would give optimal performance on S3?

<details>
<summary>Click to answer</summary>

- [x] HH-DD-MM-YYYY-log_instancelD.   

</details>

0.   Sequential.

1.   instancelD_log-HH-DD-MM-YYYY.

2.   instancelDJog-YYYY-MM-DD-HH.

3.   HH-DD-MM-YYYY-log_instancelD.

4.   YYYY-MM-DD-HH-logJnstancelD.


### Which of the following statements about SQS is true?

<details>
<summary>Click to answer</summary>

- [x] Messages will be delivered one or more times and messages will be delivered in First in, First out order.   

</details>

0.   Messages will be delivered exactly once and messages will be delivered in First in, First out order.

1.   Messages will be delivered exactly once and message delivery order is indeterminate.

2.   Messages will be delivered one or more times and messages will be delivered in First in, First out order.

3.   Messages will be delivered one or more times and message delivery order is indeterminate.


### A corporate web application is deployed within an Amazon VPC, and is connected to the corporate data center via IPSec VPN. The application must authenticate against the on-premise LDAP server. Once authenticated, logged-in users can only access an S3 keyspace specific to the user. Which two approaches can satisfy the objectives? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] The application authenticates against LDAP, and retrieves the name of an IAM role associated with the user. The application then calls the IAM Security Token Service to assume that IAM Role. The application can use the temporary credentials to access the appropriate S3 bucket.
- [x] Develop an identity broker which authenticates against LDAP, and then calls IAM Security Token Service to get IAM federated user credentials. The application calls the identity broker to get IAM federated user credentials with access to the appropriate S3 bucket.   

</details>

0.   The application authenticates against LDAP. The application then calls the IAM Security Service to login to IAM using the LDAP credentials. The application can use the 1AM temporary credentials to access the appropriate S3 bucket.

1.   The application authenticates against LDAP, and retrieves the name of an IAM role associated with the user. The application then calls the IAM Security Token Service to assume that IAM Role. The application can use the temporary credentials to access the appropriate S3 bucket.

2.   The application authenticates against IAM Security Token Service using the LDAP credentials. The application uses those temporary AWS security credentials to access the appropriate S3 bucket.

3.   Develop an identity broker which authenticates against LDAP, and then calls IAM Security Token Service to get IAM federated user credentials. The application calls the identity broker to get IAM federated user credentials with access to the appropriate S3 bucket.

4.   Develop an identity broker which authenticates against IAM Security Token Service to assume an IAM Role to get temporary AWS security credentials. The application calls the identity broker to get AWS temporary security credentials with access to the appropriate S3 bucket.


### Company C is currently hosting their corporate site in an Amazon S3 bucket with Static Website Hosting enabled. Currently, when visitors go to http://www.companyc.com the index.html page is returned. Company C now would like a new page welcome.html to be returned when a visitor enters http://www.companyc.com in the browser. Which of the following steps will allow Company C to meet this requirement? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Upload an html page named welcome.html to their S3 bucket.
- [x] Set the Index Document property to welcome.html.   

</details>

0.   Upload an html page named welcome.html to their S3 bucket.

1.   Create a welcome subfolder in their S3 bucket.

2.   Set the Index Document property to welcome.html.

3.   Move the index.html page to a welcome subfolder.

4.   Set the Error Document property to welcome.html.


### What type of block cipher does Amazon S3 offer for server side encryption?

<details>
<summary>Click to answer</summary>

- [x] Advanced Encryption Standard.   

</details>

0.   Triple DES.

1.   Advanced Encryption Standard.

2.   Blowfish.

3.   RC5.


### A Development team wants to instrument their code to provide more detailed information to AWS X-Ray than simple outgoing and incoming requests. This will generate large amounts of data, so the Development team wants to implement indexing so they can filter the data. What should the Development team do to achieve this?

<details>
<summary>Click to answer</summary>

- [x] Add annotations to the segment document and the code.   

</details>

0.   Add annotations to the segment document and the code.

1.   Add metadata to the segment document and the code.

2.   Configure the necessary X-Ray environment variables.

3.   Install required plugins for the appropriate AWS SDK.


### A team of Developers must migrate an application running inside an AWS Elastic Beanstalk environment from a Classic Load Balancer to an Application Load Balancer. Which steps should be taken to accomplish the task using the AWS Management Console?

<details>
<summary>Click to answer</summary>

- [x] 1. Update the application code in the existing deployment. 2. Select a new load balancer type before running the deployment. 3. Deploy the new version of the application code to the environment.   

</details>

0.   1. Update the application code in the existing deployment. 2. Select a new load balancer type before running the deployment. 3. Deploy the new version of the application code to the environment.

1.   1. Create a new environment with the same configurations except for the load balancer type. 2. Deploy the same application version as used in the original environment. 3. Run the swap-environment-cnames action.

2.   1. Clone the existing environment, changing the associated load balancer type. 2. Deploy the same application version as used in the original environment. 3. Run the swap-environment-cnames action.

3.   1. Edit the environment definitions in the existing deployment. 2. Change the associated load balancer type according to the requirements. 3. Rebuild the environment with the new load balancer type.


### A company needs a version control system for collaborative software development. Features of the system must include the following: Support for batches of changes across multiple files Parallel branching Version tracking Which AWS service will meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] AWS CodeCommit.   

</details>

0.   AWS CodePipeline.

1.   Amazon S3.

2.   AWS Code Build.

3.   AWS CodeCommit.


### A company is using continuous integration and continuous delivery systems. A Developer now needs to automate a software package deployment to both Amazon EC2 instances and virtual servers running on-premises. Which AWS service should be used to accomplish this?

<details>
<summary>Click to answer</summary>

- [x] AWS CodeDeploy.   

</details>

0.   AWS CodePipeline.

1.   AWS CodeBuild.

2.   AWS Elastic Beanstalk.

3.   AWS CodeDeploy.


### A Developer created a new AWS account and must create a scalable AWS Lambda function that meets the following requirements for concurrent execution: Average execution time of 100 seconds 50 requests per second. Which step must be taken prior to deployment to prevent errors?

<details>
<summary>Click to answer</summary>

- [x] Add an event source from Amazon API Gateway to the Lambda function.   

</details>

0.   Implement dead-letter queues to capture invocation errors.

1.   Add an event source from Amazon API Gateway to the Lambda function.

2.   Implement error handling within the application code.

3.   Contact AWS Support to increase the concurrent execution limits.


### A Developer is building a three-tier web application that should be able to handle a minimum of 5000 requests per minute. Requirements state that the web tier should be completely stateless while the application maintains session state for the users. How can session data be externalized, keeping latency at the LOWEST possible value?

<details>
<summary>Click to answer</summary>

- [x] Create an Amazon RDS instance, then implement session handling at the application level to leverage a database inside the RDS database instance for session data storage.   

</details>

0.   Create an Amazon RDS instance, then implement session handling at the application level to leverage a database inside the RDS database instance for session data storage.

1.   Implement a shared file system solution across the underlying Amazon EC2 instances, then implement session handling at the application level to leverage the shared file system for session data storage.

2.   Create an Amazon ElastiCache Memcached cluster, then implement session handling at the application level to leverage the cluster for session data storage.

3.   Create an Amazon DynamoDB table, then implement session handling at the application level to leverage the table for session data storage.


### An Amazon DynamoDB table uses a Global Secondary Index (GSI) to support read queries. The primary table is write-heavy, whereas the GSI is used for read operations. Looking at Amazon CloudWatch metrics, the Developer notices that write operations to the primary table are throttled frequently under heavy write activity. However, write capacity units to the primary table are available and not fully consumed. Why is the table being throttled?

<details>
<summary>Click to answer</summary>

- [x] A large write operation is being performed against another table.   

</details>

0.   The GSI write capacity units are underprovisioned.

1.   There are not enough read capacity units on the primary table.

2.   Amazon DynamoDB Streams is not enabled on the table.

3.   A large write operation is being performed against another table.


### A company runs an e-commerce website that uses Amazon DynamoDB where pricing for items is dynamically updated in real time. At any given time, multiple updates may occur simultaneously for pricing information on a particular product. This is causing the original editor's changes to be overwritten without a proper review process. Which DynamoDB write option should be selected to prevent this overwriting?

<details>
<summary>Click to answer</summary>

- [x] Conditional writes.   

</details>

0.   Concurrent writes.

1.   Conditional writes.

2.   Atomic writes.

3.   Batch writes.


### A Developer has been asked to create an AWS Lambda function that is triggered any time updates are made to items in an Amazon DynamoDB table. The function has been created, and appropriate permissions have been added to the Lambda execution role. Amazon DynamoDB streams have been enabled for the table, but the function is still not being triggered. Which option would enable DynamoDB table updates to trigger the Lambda function?

<details>
<summary>Click to answer</summary>

- [x] Change the StreamViewType parameter value to NEW_AND_OLD_IMAGES for the DynamoDB table.   

</details>

0.   Change the StreamViewType parameter value to NEW_AND_OLD_IMAGES for the DynamoDB table.

1.   Configure event source mapping for the Lambda function.

2.   Map an Amazon SNS topic to the DynamoDB streams.

3.   Increase the maximum execution time (timeout) setting of the Lambda function.


### A company is running a Docker application on Amazon ECS. The application must scale based on user load in the last 15 seconds. How should a Developer instrument the code so that the requirement can be met?

<details>
<summary>Click to answer</summary>

- [x] Create a high-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 5 seconds.   

</details>

0.   Create a high-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 30 seconds.

1.   Create a high-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 5 seconds.

2.   Create a standard-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 30 seconds.

3.   Create a standard-resolution custom Amazon CloudWatch metric for user activity data, then publish data every 5 seconds.


### A company needs to ingest terabytes of data each hour from thousands of sources that are delivered almost continually throughout the day. The volume of messages generated varies over the course of the day. Messages must be delivered in real time for fraud detection and live operational dashboards. Which approach will meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon Kinesis Data Streams with Kinesis Client Library to ingest and deliver messages.   

</details>

0.   Send the messages to an Amazon SQS queue, then process the messages by using a fleet of Amazon EC2 instances.

1.   Use the Amazon S3 API to write messages to an S3 bucket, then process the messages by using Amazon Redshift.

2.   Use AWS Data Pipeline to automate the movement and transformation of data.

3.   Use Amazon Kinesis Data Streams with Kinesis Client Library to ingest and deliver messages.


### A Developer accesses AWS CodeCommit over SSH. The SSH keys configured to access AWS CodeCommit are tied to a user with the following permissions. The Developer needs to create/delete branches. Which specific IAM permissions need to be added, based on the principle of least privilege?

<details>
<summary>Click to answer</summary>

- [x] "codecommit:CreateBranch" "codecommit:DeleteBranch".   

</details>

0.   "codecommit:CreateBranch" "codecommit:DeleteBranch".

1.   "codecommit:Put*".

2.   "codecommit:Update*".

3.   "codecommit:*".


### An AWS Lambda function must access an external site by using a regularly rotated user name and password. These items must be kept securely and cannot be stored in the function code. What combination of AWS services can be used to accomplish this? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] AWS Systems Manager Parameter Store.
- [x] AWS KMS.   

</details>

0.   AWS Certificate Manager (ACM).

1.   AWS Systems Manager Parameter Store.

2.   AWS Trusted Advisor.

3.   AWS KMS.

4.   Amazon GuardDuty.


### A Developer is trying to deploy a serverless application using AWS CodeDeploy. The application was updated and needs to be redeployed. What file does the Developer need to update to push that change through CodeDeploy?

<details>
<summary>Click to answer</summary>

- [x] appspec.yml   

</details>

0.   dockerrun.aws.json

1.   buildspec.yml

2.   appspec.yml

3.   ebextensions.config


### A Developer is working on an application that handles 10MB documents that contain highly-sensitive data. The application will use AWS KMS to perform clientside encryption. What steps must be followed?

<details>
<summary>Click to answer</summary>

- [x] Invoke the Encrypt API passing the plaintext data that must be encrypted, then reference the customer managed key ARN in the KeyId parameter.   

</details>

0.   Invoke the Encrypt API passing the plaintext data that must be encrypted, then reference the customer managed key ARN in the KeyId parameter.

1.   Invoke the GenerateRandom API to get a data encryption key, then use the data encryption key to encrypt the data.

2.   Invoke the GenerateDataKey API to retrieve the encrypted version of the data encryption key to encrypt the data.

3.   Invoke the GenerateDataKey API to retrieve the plaintext version of the data encryption key to encrypt the data.


### A Developer is building a web application that uses Amazon API Gateway to expose an AWS Lambda function to process requests from clients. During testing, the Developer notices that the API Gateway times out even though the Lambda function finishes under the set time limit. Which of the following API Gateway metrics in Amazon CloudWatch can help the Developer troubleshoot the issue? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] CacheHitCount.
- [x] Latency.   

</details>

0.   CacheHitCount.

1.   IntegrationLatency.

2.   CacheMissCount.

3.   Latency.

4.   Count.


### A company needs to distribute firmware updates to its customers around the world. Which service will allow easy and secure control of the access to the downloads at the lowest cost?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon CloudFront with signed URLs for Amazon S3.   

</details>

0.   Use Amazon CloudFront with signed URLs for Amazon S3.

1.   Create a dedicated Amazon CloudFront Distribution for each customer.

2.   Use Amazon CloudFront with AWS Lambda@Edge.

3.   Use Amazon API Gateway and AWS Lambda to control access to an S3 bucket.


### An application writes items to an Amazon DynamoDB table. As the application scales to thousands of instances, calls to the DynamoDB API generate occasional ThrottlingException errors. The application is coded in a language incompatible with the AWS SDK. How should the error be handled?

<details>
<summary>Click to answer</summary>

- [x] Add exponential backoff to the application logic.   

</details>

0.   Add exponential backoff to the application logic.

1.   Use Amazon SQS as an API message bus.

2.   Pass API calls through Amazon API Gateway.

3.   Send the items to DynamoDB through Amazon Kinesis Data Firehose.


### An e-commerce web application that shares session state on-premises is being migrated to AWS. The application must be fault tolerant, natively highly scalable, and any service interruption should not affect the user experience. What is the best option to store the session state?

<details>
<summary>Click to answer</summary>

- [x] Store the session state in Amazon ElastiCache.   

</details>

0.   Store the session state in Amazon ElastiCache.

1.   Store the session state in Amazon CloudFront.

2.   Store the session state in Amazon S3.

3.   Enable session stickiness using elastic load balancers.


### A Developer is creating a template that uses AWS CloudFormation to deploy an application. This application is serverless and uses Amazon API Gateway, Amazon DynamoDB, and AWS Lambda. Which tool should the Developer use to define simplified syntax for expressing serverless resources?

<details>
<summary>Click to answer</summary>

- [x] An AWS serverless application model.   

</details>

0.   CloudFormation serverless intrinsic functions.

1.   AWS serverless express.

2.   An AWS serverless application model.

3.   A CloudFormation serverless plugin.


### A Developer has a stateful web server on-premises that is being migrated to AWS. The Developer must have greater elasticity in the new design. How should the Developer re-factor the application to make it more elastic? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Store session state data in an Amazon DynamoDB table.
- [x] Use an ELB with an Auto Scaling group.   

</details>

0.   Use pessimistic concurrency on Amazon DynamoDB.

1.   Use Amazon CloudFront with an Auto Scaling group.

2.   Use Amazon CloudFront with an AWS Web Application Firewall.

3.   Store session state data in an Amazon DynamoDB table.

4.   Use an ELB with an Auto Scaling group.


### A Developer must analyze performance issues with production-distributed applications written as AWS Lambda functions. These distributed Lambda applications invoke other components that make up the applications. How should the Developer identify and troubleshoot the root cause of the performance issues in production?

<details>
<summary>Click to answer</summary>

- [x] Use AWS X-Ray, then examine the segments and errors.   

</details>

0.   Add logging statements to the Lambda functions, then use Amazon CloudWatch to view the logs.

1.   Use AWS Cloud Trail and then examine the logs.

2.   Use AWS X-Ray, then examine the segments and errors.

3.   Run Amazon Inspector agents and then analyze performance.


### A Developer wants to debug an application by searching and filtering log data. The application logs are stored in Amazon CloudWatch Logs. The Developer creates a new metric filter to count exceptions in the application logs. However, no results are returned from the logs. What is the reason that no filtered results are being returned?

<details>
<summary>Click to answer</summary>

- [x] CloudWatch Logs only publishes metric data for events that happen after the filter is created.   

</details>

0.   A setup of the Amazon CloudWatch interface VPC endpoint is required for filtering the CloudWatch Logs in the VPC.

1.   CloudWatch Logs only publishes metric data for events that happen after the filter is created.

2.   The log group for CloudWatch Logs should be first streamed to Amazon Elasticsearch Service before metric filtering returns the results.

3.   Metric data points for logs groups can be filtered only after they are exported to an Amazon S3 bucket.


### To include objects defined by the AWS Serverless Application Model (SAM) in an AWS CloudFormation template, in addition to Resources, what section MUST be included in the document root?

<details>
<summary>Click to answer</summary>

- [x] Properties.   

</details>

0.   Conditions.

1.   Globals.

2.   Transform.

3.   Properties.


### A company is using Amazon RDS MySQL instances for its application database tier and Apache Tomcat servers for its web tier. Most of the database queries from web applications are repeated read requests. Use of which AWS service would increase in performance by adding in-memory store for repeated read queries?

<details>
<summary>Click to answer</summary>

- [x] Amazon RDS Multi-AZ.   

</details>

0.   Amazon RDS Multi-AZ.

1.   Amazon SQS.

2.   Amazon ElastiCache.

3.   Amazon RDS read replica.


### A Developer is investigating an issue whereby certain requests are passing through an Amazon API Gateway endpoint /MyAPI, but the requests do not reach the AWS Lambda function backing /MyAPI. The Developer found that a second Lambda function sometimes runs at maximum concurrency allowed for the given AWS account. How can the Developer address this issue?

<details>
<summary>Click to answer</summary>

- [x] Configure the second Lambda function's concurrency execution limit.   

</details>

0.   Manually reduce the concurrent execution limit at the account level.

1.   Add another API Gateway stage for /MyAPI, and shard the requests.

2.   Configure the second Lambda function's concurrency execution limit.

3.   Reduce the throttling limits in the API Gateway /MyAPI endpoint


### A company is migrating a single-server, on-premises web application to AWS. The company intends to use multiple servers behind an Elastic Load Balancer (ELB) to balance the load, and will also store session data in memory on the web server. The company does not want to lose that session data if a server fails or goes offline, and it wants to minimize user's downtime. Where should the company move session data to MOST effectively reduce downtime and make users' session data more fault tolerant?

<details>
<summary>Click to answer</summary>

- [x] An Amazon ElastiCache for Redis cluster.   

</details>

0.   An Amazon ElastiCache for Redis cluster.

1.   A second Amazon EBS volume.

2.   The web server's primary disk.

3.   An Amazon EC2 instance dedicated to session data.


### A Developer created configuration specifications for an AWS Elastic Beanstalk application in a file named healthcheckurl.yaml in the .ebextensions/directory of their application source bundle. The file contains the following: After the application launches, the health check is not being run on the correct path, even though it is valid. What can be done to correct this configuration file?

<details>
<summary>Click to answer</summary>

- [x] Rename the file to a .config extension.   

</details>

0.   Convert the file to JSON format.

1.   Rename the file to a .config extension.

2.   Change the configuration section from options_settings to resources.

3.   Change the namespace of the option settings to a custom namespace.


### A Developer has created a Lambda function and is finding that the function is taking longer to complete than expected. After some debugging, the Developer has discovered that increasing compute capacity would improve performance. How can the Developer increase the Lambda compute resources?

<details>
<summary>Click to answer</summary>

- [x] Specify a larger compute capacity when calling the Lambda function.   

</details>

0.   Run on a larger instance size with more compute capacity.

1.   Increase the maximum execution time.

2.   Specify a larger compute capacity when calling the Lambda function.

3.   Increase the allocated memory for the Lambda function.


### An e-commerce site allows returning users to log in to display customized web pages. The workflow is shown in the image below. An application is running on EC2 instances. Amazon RDS is used for the database that stores user accounts and preferences. The website freezes or is slow to load while waiting for the login step to complete. The remaining components of the site are well-optimized. Which of the following techniques will resolve this issue? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Use Amazon ElastiCache for MemCached to cache user data.
- [x] Call the database asynchronously so the code can continue executing.   

</details>

0.   Implement the user login page as an asynchronous Lambda function.

1.   Use Amazon ElastiCache for MemCached to cache user data.

2.   Use Amazon Application Load Balancer to load balance the traffic to the website.

3.   Call the database asynchronously so the code can continue executing.

4.   Batch login requests from hundreds of users together as a single read request to the database.


### A Developer is building a mobile application and needs any update to user profile data to be pushed to all devices accessing the specific identity. The Developer does not want to manage a back end to maintain the user profile data. What is the MOST efficient way for the Developer to achieve these requirements using Amazon Cognito?

<details>
<summary>Click to answer</summary>

- [x] Use Cognito federated identities.   

</details>

0.   Use Cognito federated identities.

1.   Use a Cognito user pool.

2.   Use Cognito Sync.

3.   Use Cognito events.


### A company maintains a REST service using Amazon API Gateway and the API Gateway native API key validation. The company recently launched a new registration page, which allows users to sign up for the service. The registration page creates a new API key using CreateApiKey and sends the new key to the user. When the user attempts to call the API using this key, the user receives a 403 Forbidden error. Existing users are unaffected and can still call the API. What code updates will grant these new users access to the API?

<details>
<summary>Click to answer</summary>

- [x] The importApiKeys method must be called to import all newly created API keys into the current stage of the API.   

</details>

0.   The createDeployment method must be called so the API can be redeployed to include the newly created API key.

1.   The updateAuthorizer method must be called to update the API's authorizer to include the newly created API key.

2.   The importApiKeys method must be called to import all newly created API keys into the current stage of the API.

3.   The createUsagePlanKey method must be called to associate the newly created API key with the correct usage plan.


### A Developer is writing a mobile application that allows users to view images from an S3 bucket. The users must be able to log in with their Amazon login, as well as Facebook and/or Google accounts. How can the Developer provide this authentication functionality?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon Cognito with web identity federation.   

</details>

0.   Use Amazon Cognito with web identity federation.

1.   Use Amazon Cognito with SAML-based identity federation.

2.   Use AWS IAM Access/Secret keys in the application code to allow Get* on the S3 bucket.

3.   Use AWS STS AssumeRole in the application code and assume a role with Get* permissions on the S3 bucket.


### A Developer wants access to make the log data of an application running on an EC2 instance available to systems administrators. Which of the following enables monitoring of this metric in Amazon CloudWatch?

<details>
<summary>Click to answer</summary>

- [x] Install the Amazon CloudWatch Logs agent on the EC2 instance that the application is running on.   

</details>

0.   Retrieve the log data from CloudWatch using the GetMetricData API call.

1.   Retrieve the log data from AWS CloudTrail using the LookupEvents API call.

2.   Launch a new EC2 instance, configure Amazon CloudWatch Events, and then install the application.

3.   Install the Amazon CloudWatch Logs agent on the EC2 instance that the application is running on.


### A nightly batch job loads 1 million new records into a DynamoDB table. The records are only needed for one hour, and the table needs to be empty by the next night's batch job. Which is the MOST efficient and cost-effective method to provide an empty table?

<details>
<summary>Click to answer</summary>

- [x] Use DeleteItem using a ConditionExpression.   

</details>

0.   Use DeleteItem using a ConditionExpression.

1.   Use BatchWriteItem to empty all of the rows.

2.   Write a recursive function that scans and calls out DeleteItem.

3.   Create and then delete the table after the task has completed.


### A company has an application that logs all information to Amazon S3. Whenever there is a new log file, an AWS Lambda function is invoked to process the log files. The code works, gathering all of the necessary information. However, when checking the Lambda function logs, duplicate entries with the same request ID are found. What is causing the duplicate entries?

<details>
<summary>Click to answer</summary>

- [x] The Lambda function failed, and the Lambda service retired the invocation with a delay.   

</details>

0.   The S3 bucket name was specified incorrectly.

1.   The Lambda function failed, and the Lambda service retired the invocation with a delay.

2.   There was an S3 outage, which caused duplicate entries of the sale log file.

3.   The application stopped intermittently and then resumed.


### A company is providing services to many downstream consumers. Each consumer may connect to one or more services. This has resulted in a complex architecture that is difficult to manage and does not scale well. The company needs a single interface to manage these services to consumers. Which AWS service should be used to refactor this architecture?

<details>
<summary>Click to answer</summary>

- [x] Amazon API Gateway.   

</details>

0.   AWS Lambda.

1.   AWS X-Ray.

2.   Amazon SQS.

3.   Amazon API Gateway.


### A Developer is creating a serverless website with content that includes HTML files, images, videos, and JavaScript (client-side scripts). Which combination of services should the Developer use to create the website?

<details>
<summary>Click to answer</summary>

- [x] Amazon S3 and Amazon CloudFront.   

</details>

0.   Amazon S3 and Amazon CloudFront.

1.   Amazon EC2 and Amazon ElastiCache.

2.   Amazon ECS and Redis.

3.   AWS Lambda and Amazon API Gateway.


### A Development team has pushed out 10 applications running on several Amazon EC2 instances. The Operations team is asking for a graphical representation of one key performance metric for each application. These metrics should be available on one screen for easy monitoring. Which steps should the Developer take to accomplish this using Amazon CloudWatch?

<details>
<summary>Click to answer</summary>

- [x] Create a custom dimension with a unique metric name for each application.   

</details>

0.   Create a custom namespace with a unique metric name for each application.

1.   Create a custom dimension with a unique metric name for each application.

2.   Create a custom event with a unique metric name for each application.

3.   Create a custom alarm with a unique metric name for each application.


### A company is creating an application that will require users to access AWS services and allow them to reset their own passwords. Which of the following would allow the company to manage users and authorization while allowing users to reset their own passwords?

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito identity pools and AWS IAM.   

</details>

0.   Amazon Cognito identify pools and AWS STS.

1.   Amazon Cognito identity pools and AWS IAM.

2.   Amazon Cognito user pools and AWS KMS.

3.   Amazon Cognito user pools and identity pools.


### A company has three different environments: Development, QA, and Production. The company wants to deploy its code first in the Development environment, then QA, and then Production. Which AWS service can be used to meet this requirement?

<details>
<summary>Click to answer</summary>

- [x] Use AWS Data Pipeline to create multiple data pipeline provisions to deploy the application.   

</details>

0.   Use AWS CodeCommit to create multiple repositories to deploy the application.

1.   Use AWS CodeBuild to create, configure, and deploy multiple build application projects.

2.   Use AWS Data Pipeline to create multiple data pipeline provisions to deploy the application.

3.   Use AWS CodeDeploy to create multiple deployment groups.


### A company uses Amazon DynamoDB for managing and tracking orders. The DynamoDB table is partitioned based on the order date. The company receives a huge increase in orders during a sales event, causing DynamoDB writes to throttle, and the consumed throughput is far below the provisioned throughput. According to AWS best practices, how can this issue be resolved with MINIMAL costs?

<details>
<summary>Click to answer</summary>

- [x] Increase the read and write capacity units of the DynamoDB table.   

</details>

0.   Create a new DynamoDB table for every order date.

1.   Increase the read and write capacity units of the DynamoDB table.

2.   Add a random number suffix to the partition key values.

3.   Add a global secondary index to the DynamoDB table.


### A Development team currently supports an application that uses an in-memory store to save accumulated game results. Individual results are stored in a database. As part of migrating to AWS, the team needs to use automatic scaling. The team knows this will yield inconsistent results. Where should the team store these accumulated game results to BEST allow for consistent results without impacting performance?

<details>
<summary>Click to answer</summary>

- [x] Amazon ElastiCache.   

</details>

0.   Amazon S3.

1.   Amazon RDS.

2.   Amazon ElastiCache.

3.   Amazon Kinesis.


### In a multi-container Docker environment in AWS Elastic Beanstalk, what is required to configure container instances in the environment?

<details>
<summary>Click to answer</summary>

- [x] An Amazon ECS task definition.   

</details>

0.   An Amazon ECS task definition.

1.   An Amazon ECS cluster.

2.   A Dockerfile in an application package.

3.   A CLI for Elastic Beanstalk.


### An application that runs on an Amazon EC2 instance needs to access and make API calls to multiple AWS services. What is the MOST secure way to provide access to the AWS services with MINIMAL management overhead?

<details>
<summary>Click to answer</summary>

- [x] Use AWS root user to make requests to the application.   

</details>

0.   Use AWS KMS to store and retrieve credentials.

1.   Use EC2 instance profiles.

2.   Use AWS root user to make requests to the application.

3.   Store and retrieve credentials from AWS CodeCommit.


### A company maintains an application responsible for processing several thousand external callbacks each day. The company's System administrators want to know how many callbacks are being received on a rolling basis, and they want this data available for 10 days. The company also wants the ability to issue automated alerts if the number of callbacks exceeds the defined thresholds. What is the MOST cost-effective way to address the need to track and alert on these statistics?

<details>
<summary>Click to answer</summary>

- [x] Push callback data to Amazon Kinesis Data Streams and invoke an AWS Lambda function that stores data in Amazon DynamoDB and sends the required alerts.   

</details>

0.   Push callback data to an Amazon RDS database that can be queried to show historical data and to alert on exceeded thresholds.

1.   Push callback data to AWS X-Ray and use AWS Lambda to query, display, and alert on exceeded thresholds.

2.   Push callback data to Amazon Kinesis Data Streams and invoke an AWS Lambda function that stores data in Amazon DynamoDB and sends the required alerts.

3.   Push callback data to Amazon CloudWatch as a custom metric and use the CloudWatch alerting mechanisms to alert System Administrators.


### A company has a website that is developed in PHP and WordPress and is launched using AWS Elastic Beanstalk. There is a new version of the website that needs to be deployed in the Elastic Beanstalk environment. The company cannot tolerate having the website offline if an update fails. Deployments must have minimal impact and rollback as soon as possible. What deployment method should be used?

<details>
<summary>Click to answer</summary>

- [x] Immutable.   

</details>

0.   All at once.

1.   Rolling.

2.   Snapshots.

3.   Immutable.


### A company has a multi-tiered web application on AWS. During a recent spike in traffic, one of the primary relational databases on Amazon RDS could not serve all the traffic. Some read queries for repeatedly accessed items failed, so users received error messages. What can be done to minimize the impact on database read queries MOST efficiently during future traffic spikes?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon RDS as a custom origin for Amazon CloudFront.   

</details>

0.   Use Amazon S3 to cache database query results.

1.   Use Amazon RDS as a custom origin for Amazon CloudFront.

2.   Use local storage and memory on Amazon EC2 instances to cache data.

3.   Use Amazon ElastiCache in front of the primary database to cache data.


### A Developer must build an application that uses Amazon DynamoDB. The requirements state that the items being stored in the DynamoDB table will be 7KB in size and that reads must be strongly consistent. The maximum read rate is 3 items per second, and the maximum write rate is 10 items per second. How should the Developer size the DynamoDB table to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Read: 6 read capacity unitsWrite: 70 write capacity units.   

</details>

0.   Read: 3 read capacity unitsWrite: 70 write capacity units.

1.   Read: 6 read capacity unitsWrite: 70 write capacity units.

2.   Read: 6 read capacity unitsWrite: 10 write capacity units.

3.   Read: 3 read capacity unitsWrite: 10 write capacity units.


### A Developer is creating an AWS Lambda function to process a stream of data from an Amazon Kinesis Data Stream. When the Lambda function parses the data and encounters a missing field, it exits the function with an error. The function is generating duplicate records from the Kinesis stream. When the Developer looks at the stream output without the Lambda function, there are no duplicate records. What is the reason for the duplicates?

<details>
<summary>Click to answer</summary>

- [x] The Lambda function did not advance the Kinesis stream pointer to the next record after the error.   

</details>

0.   The Lambda function did not advance the Kinesis stream pointer to the next record after the error.

1.   The Lambda event source used asynchronous invocation, resulting in duplicate records.

2.   The Lambda function did not handle the error, and the Lambda service attempted to reprocess the data.

3.   The Lambda function is not keeping up with the amount of data coming from the stream.


### A company is developing an application that will run on several Amazon EC2 instances in an Auto Scaling group and can access a database running on Amazon EC2. The application needs to store secrets required to connect to the database. The application must allow for periodic secret rotation, and there should be no changes to the application when a secret changes. What is the SAFEST way to meet these requirements?

<details>
<summary>Click to answer</summary>

- [x] Associate an IAM role to the EC2 instance where the application is running with permission to access the database.   

</details>

0.   Associate an IAM role to the EC2 instance where the application is running with permission to access the database.

1.   Use AWS Systems Manager Parameter Store with the SecureString data type to store secrets.

2.   Configure the application to store secrets in Amazon S3 object metadata.

3.   Hard code the database secrets in the application code itself.


### A Developer writes an AWS Lambda function and uploads the code in a .ZIP file to Amazon S3. The Developer makes changes to the code and uploads a new.ZIP file to Amazon S3. However, Lambda executes the earlier code. How can the Developer fix this in the LEAST disruptive way?

<details>
<summary>Click to answer</summary>

- [x] Call the update-function-code API.   

</details>

0.   Create another Lambda function and specify the new .ZIP file.

1.   Call the update-function-code API.

2.   Remove the earlier .ZIP file first, then add the new .ZIP file.

3.   Call the create-alias API.


### An AWS Lambda function must read data from an Amazon RDS MySQL database in a VPC and also reach a public endpoint over the internet to get additional data. Which steps must be taken to allow the function to access both the RDS resource and the public endpoint? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Modify the default configuration for the Lambda function to associate it with an Amazon VPC private subnet.
- [x] Add a NAT Gateway to the VPC.   

</details>

0.   Modify the default configuration for the Lambda function to associate it with an Amazon VPC private subnet.

1.   Modify the default network access control list to allow outbound traffic.

2.   Add a NAT Gateway to the VPC.

3.   Modify the default configuration of the Lambda function to associate it with a VPC public subnet.

4.   Add an environmental variable to the Lambda function to allow outbound internet access.


### A Developer has been asked to make changes to the source code of an AWS Lambda function. The function is managed using an AWS CloudFormation template. The template is configured to load the source code from an Amazon S3 bucket. The Developer manually created a .ZIP file deployment package containing the changes and put the file into the correct location on Amazon S3. When the function is invoked, the code changes have not been applied. What step is required to update the function with the changes?

<details>
<summary>Click to answer</summary>

- [x] Modify the execution role of the Lambda function to allow S3 access permission to the deployment package .ZIP file.   

</details>

0.   Delete the .ZIP file on S3, and re-upload by using a different object key name.

1.   Update the CloudFormation stack with the correct values for the function code properties S3Bucket, S3Key, or S3ObjectVersion.

2.   Ensure that the function source code is base64-encoded before uploading the deployment package to S3.

3.   Modify the execution role of the Lambda function to allow S3 access permission to the deployment package .ZIP file.


### A Developer wants to enable AWS X-Ray for a secure application that runs in an Amazon ECS environment. What combination of steps will enable X-Ray? (Select THREE)

<details>
<summary>Click to answer</summary>

- [x] Add instrumentation to the application code for X-Ray.
- [x] Install the X-Ray daemon on the underlying EC2 instance.
- [x] Configure and use an IAM EC2 instance role.   

</details>

0.   Create a Docker image that runs the X-Ray daemon.

1.   Add instrumentation to the application code for X-Ray.

2.   Install the X-Ray daemon on the underlying EC2 instance.

3.   Configure and use an IAM EC2 instance role.

4.   Register the application with X-Ray.

5.   Configure and use an IAM role for tasks.


### A Developer is designing a new application that uses Amazon S3. To satisfy compliance requirements, the Developer must encrypt the data at rest. How can the Developer accomplish this?

<details>
<summary>Click to answer</summary>

- [x] Turn on S3 default encryption for the S3 bucket.   

</details>

0.   Use s3:x-amz-acl as a condition in the S3 bucket policy.

1.   Use Amazon RDS with default encryption.

2.   Use aws:SecureTransport as a condition in the S3 bucket policy.

3.   Turn on S3 default encryption for the S3 bucket.


### An AWS Elastic Beanstalk application needs to be deployed in multiple regions and requires a different Amazon Machine Image (AMI) in each region. Which AWS CloudFormation template key can be used to specify the correct AMI for each region?

<details>
<summary>Click to answer</summary>

- [x] Mappings.   

</details>

0.   Parameters.

1.   Outputs.

2.   Mappings.

3.   Resources.


### A Developer wants to find a list of items in a global secondary index from an Amazon DynamoDB table. Which DynamoDB API call can the Developer use in order to consume the LEAST number of read capacity units?

<details>
<summary>Click to answer</summary>

- [x] Query operation using eventually-consistent reads.   

</details>

0.   Scan operation using eventually-consistent reads.

1.   Query operation using strongly-consistent reads.

2.   Query operation using eventually-consistent reads.

3.   Scan operation using strongly-consistent reads.


### A Developer has published an update to an application that is served to a global user base using Amazon CloudFront. After deploying the application, users are not able to see the updated changes. How can the Developer resolve this issue?

<details>
<summary>Click to answer</summary>

- [x] Remove the origin from the CloudFront configuration and add it again.   

</details>

0.   Remove the origin from the CloudFront configuration and add it again.

1.   Disable forwarding of query strings and request headers from the CloudFront distribution configuration.

2.   Invalidate all the application objects from the edge caches.

3.   Disable the CloudFront distribution and enable it again to update all the edge locations.


### A Developer must deploy a new AWS Lambda function using an AWS CloudFormation template. Which procedures will deploy a Lambda function? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Create an AWS::Lambda::Function resource in the template, then write the code directly inside the CloudFormation template.
- [x] Upload a .ZIP file to AWS CloudFormation containing the function code, then add a reference to it in an AWS::Lambda::Function resource in the template.   

</details>

0.   Upload the code to an AWS CodeCommit repository, then add a reference to it in an AWS::Lambda::Function resource in the template.

1.   Create an AWS::Lambda::Function resource in the template, then write the code directly inside the CloudFormation template.

2.   Upload a .ZIP file containing the function code to Amazon S3, then add a reference to it in an AWS::Lambda::Function resource in the template.

3.   Upload a .ZIP file to AWS CloudFormation containing the function code, then add a reference to it in an AWS::Lambda::Function resource in the template.

4.   Upload the function code to a private Git repository, then add a reference to it in an AWS::Lambda::Function resource in the template.


### How should custom libraries be utilized in AWS Lambda?

<details>
<summary>Click to answer</summary>

- [x] Modify the function runtime to include the necessary library.   

</details>

0.   Host the library on Amazon S3 and reference to it from the Lambda function.

1.   Install the library locally and upload a ZIP file of the Lambda function.

2.   Import the necessary Lambda blueprint when creating the function.

3.   Modify the function runtime to include the necessary library.


### A company needs to secure its existing website running behind an Elastic Load Balancer. The website's Amazon EC2 instances are CPU-constrained. What should be done to secure the website while not increasing the CPU load on the EC2 web servers? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Configure SSL certificates on an Elastic Load Balancer.
- [x] Install SSL certificates on the EC2 instances.   

</details>

0.   Configure an Elastic Load Balancer with SSL pass-through.

1.   Configure SSL certificates on an Elastic Load Balancer.

2.   Configure an Elastic Load Balancer with a Loadable Storage System.

3.   Install SSL certificates on the EC2 instances.

4.   Configure an Elastic Load Balancer with SSL termination.


### A Developer is writing an imaging micro service on AWS Lambda. The service is dependent on several libraries that are not available in the Lambda runtime environment. Which strategy should the Developer follow to create the Lambda deployment package?

<details>
<summary>Click to answer</summary>

- [x] Create a ZIP file with the source code and a script that installs the dependent libraries at runtime.   

</details>

0.   Create a ZIP file with the source code and all dependent libraries.

1.   Create a ZIP file with the source code and a script that installs the dependent libraries at runtime.

2.   Create a ZIP file with the source code. Stage the dependent libraries on an Amazon S3 bucket indicated by the Lambda environment variable LD_LIBRARY_PATH.

3.   Create a ZIP file with the source code and a buildspec.yaml file that installs the dependent libraries on AWS Lambda.


### A Developer is designing a fault-tolerant environment where client sessions will be saved. How can the Developer ensure that no sessions are lost if an Amazon EC2 instance fails?

<details>
<summary>Click to answer</summary>

- [x] Use sticky sessions with an Elastic Load Balancer target group.   

</details>

0.   Use sticky sessions with an Elastic Load Balancer target group.

1.   Use Amazon SQS to save session data.

2.   Use Amazon DynamoDB to perform scalable session handling.

3.   Use Elastic Load Balancer connection draining to stop sending requests to failing instances.


### In a move toward using microservices, a company's Management team has asked all Development teams to build their services so that API requests depend only on that service's data store. One team is building a Payments service which has its own database; the service needs data that originates in the Accounts database. Both are using Amazon DynamoDB. What approach will result in the simplest, decoupled, and reliable method to get near-real time updates from the Accounts database?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon DynamoDB Streams to deliver all changes from the Accounts database to the Payments database.   

</details>

0.   Use Amazon Glue to perform frequent ETL updates from the Accounts database to the Payments database.

1.   Use Amazon ElastiCache in Payments, with the cache updated by triggers in the Accounts database.

2.   Use Amazon Kinesis Data Firehouse to deliver all changes from the Accounts database to the Payments database.

3.   Use Amazon DynamoDB Streams to deliver all changes from the Accounts database to the Payments database.


### A company needs a fully-managed source control service that will work in AWS. The service must ensure that revision control synchronizes multiple distributed repositories by exchanging sets of changes peer-to-peer. All users need to work productively even when not connected to a network. Which source control service should be used?

<details>
<summary>Click to answer</summary>

- [x] AWS CodeCommit.   

</details>

0.   Subversion.

1.   AWS CodeBuild.

2.   AWS CodeCommit.

3.   AWS CodeStar.


### A Developer is writing a serverless application that requires that an AWS Lambda function be invoked every 10 minutes. What is an automated and serverless way to trigger the function?

<details>
<summary>Click to answer</summary>

- [x] Create an Amazon CloudWatch Events rule that triggers on a regular schedule to invoke the Lambda function.   

</details>

0.   Deploy an Amazon EC2 instance based on Linux, and edit its /etc/crontab file by adding a command to periodically invoke the Lambda function.

1.   Configure an environment variable named PERIOD for the Lambda function. Set the value to 600.

2.   Create an Amazon CloudWatch Events rule that triggers on a regular schedule to invoke the Lambda function.

3.   Create an Amazon SNS topic that has a subscription to the Lambda function with a 600-second timer.


### A company is building an application to track athlete performance using an Amazon DynamoDB table. Each item in the table is identified by a partition key (user_id) and a sort key (sport_name). The table design is shown below. (Note: Not all table attributes are shown) A Developer is asked to write a leaderboard application to display the top performers (user_id) based on the score for each sport_name. What process will allow the Developer to extract results MOST efficiently from the DynamoDB table?

<details>
<summary>Click to answer</summary>

- [x] Create a global secondary index with a partition key of sport_name and a sort key of score, and get the results.   

</details>

0.   Use a DynamoDB query operation with the key attributes of user_id and sport_name and order the results based on the score attribute.

1.   Create a global secondary index with a partition key of sport_name and a sort key of score, and get the results.

2.   Use a DynamoDB scan operation to retrieve scores and user_id based on sport_name, and order the results based on the score attribute.

3.   Create a local secondary index with a primary key of sport_name and a sort key of score and get the results based on the score attribute.


### A Developer is creating a mobile application that will not require users to log in. What is the MOST efficient method to grant users access to AWS resources?

<details>
<summary>Click to answer</summary>

- [x] Create credentials using AWS KMS and apply these credentials to users when using the application.   

</details>

0.   Use an identity provider to securely authenticate with the application.

1.   Create an AWS Lambda function to create an IAM user when a user accesses the application.

2.   Create credentials using AWS KMS and apply these credentials to users when using the application.

3.   Use Amazon Cognito to associate unauthenticated users with an IAM role that has limited access to resources.


### An application running on Amazon EC2 instances must access objects within an Amaon S3 busket that are encrypted using server-side encryption using AWS KMS encryption keys (SSE-KMS). The application must have access to the customer master key (CMK) to decrypt the objects. Which combination of steps will grant the application access? (Select TWO)

<details>
<summary>Click to answer</summary>

- [x] Write an S3 bucket policy that grants the bucket access to the key.
- [x] Create a Systems Manager parameter that exposes the KMS key to the EC2 instances.   

</details>

0.   Write an S3 bucket policy that grants the bucket access to the key.

1.   Grant access to the key in the IAM EC2 role attached to the application's EC2 instances.

2.   Write a key policy that enables IAM policies to grant access to the key.

3.   Grant access to the key in the S3 bucket's ACL.

4.   Create a Systems Manager parameter that exposes the KMS key to the EC2 instances.


### What does an Amazon SQS delay queue accomplish?

<details>
<summary>Click to answer</summary>

- [x] Messages are hidden for a configurable amount of time when they are first added to the queue.   

</details>

0.   Messages are hidden for a configurable amount of time when they are first added to the queue.

1.   Messages are hidden for a configurable amount of time after they are consumed from the queue.

2.   The consumer can poll the queue for a configurable amount of time before retrieving a message.

3.   Message cannot be deleted for a configurable amount of time after they are consumed from the queue.


### A company has multiple Developers located across the globe who are updating code incrementally for a development project. When Developers upload code concurrently, internet connectivity is slow and it is taking a long time to upload code for deployment in AWS Elastic Beanstalk. Which step will result in minimized upload and deployment time with the LEAST amount of administrative effort?

<details>
<summary>Click to answer</summary>

- [x] Create an AWS CodeCommit repository, allow the Developers to commit code to it, and then directly deploy the code to Elastic Beanstalk.   

</details>

0.   Allow the Developers to upload the code to an Amazon S3 bucket, and deploy it directly to Elastic Beanstalk.

1.   Allow the Developers to upload the code to a central FTP server to deploy the application to Elastic Beanstalk.

2.   Create an AWS CodeCommit repository, allow the Developers to commit code to it, and then directly deploy the code to Elastic Beanstalk.

3.   Create a code repository on an Amazon EC2 instance so that all Developers can update the code, and deploy the application from the instance to Elastic Beanstalk.


### A company recently migrated its web, application and NoSQL database tiers to AWS. The company is using Auto Scaling to scale the web and application tiers. More than 95 percent of the Amazon DynamoDB requests are repeated read requests. How can the DynamoDB NoSQL tier be scaled up to cache these repeated requests?

<details>
<summary>Click to answer</summary>

- [x] Amazon DynamoDB Accelerator.   

</details>

0.   Amazon EMR.

1.   Amazon DynamoDB Accelerator.

2.   Amazon SQS.

3.   Amazon CloudFront.


### A Development team is working on a case management solution that allows medical claims to be processed and reviewed. Users log in to provide information related to their medical and financial situations. As part of the application, sensitive documents such as medical records, medical imaging, bank statements, and receipts are uploaded to Amazon S3. All documents must be securely transmitted and stored. All access to the documents must be recorded for auditing. What is the MOST secure approach?

<details>
<summary>Click to answer</summary>

- [x] Use client-side encryption/decryption with Amazon S3 and AWS KMS.   

</details>

0.   Use S3 default encryption using Advanced Encryption Standard-256 (AES-256) on the destination bucket.

1.   Use Amazon Cognito for authorization and authentication to ensure the security of the application and documents.

2.   Use AWS Lambda to encrypt and decrypt objects as they are placed into the S3 bucket.

3.   Use client-side encryption/decryption with Amazon S3 and AWS KMS.


### A company has an internet-facing application that uses Web Identity Federation to obtain a temporary credential from AWS Security Token Service (AWS STS). The app then uses the token to access AWS services. Review the following response: Based on the response displayed what permissions are associated with the call from the application?

<details>
<summary>Click to answer</summary>

- [x] Permission associated with the IAM principal that owns the AccessKeyID ASgeIAIOSFODNN7EXAMPLE.   

</details>

0.   Permissions associated with the role AROACLKWSDQRAOEXAMPLE:app1.

1.   Permissions associated with the default role used when the AWS service was built.

2.   Permission associated with the IAM principal that owns the AccessKeyID ASgeIAIOSFODNN7EXAMPLE.

3.   Permissions associated with the account that owns the AWS service.


### A Developer is using AWS CLI, but when running list commands on a large number of resources, it is timing out. What can be done to avoid this time-out?

<details>
<summary>Click to answer</summary>

- [x] Use pagination.   

</details>

0.   Use pagination.

1.   Use shorthand syntax.

2.   Use parameter values.

3.   Use quoting strings.


### Where can PortMapping be defined when launching containers in Amazon ECS?

<details>
<summary>Click to answer</summary>

- [x] Task definition.   

</details>

0.   Security groups.

1.   Amazon Elastic Container Registry (Amzon ECR).

2.   Container agent.

3.   Task definition.


### An organization is storing large files in Amazon S3, and is writing a web application to display meta-data about the files to end-users. Based on the metadata a user selects an object to download. The organization needs a mechanism to index the files and provide single-digit millisecond latency retrieval for the metadata. What AWS service should be used to accomplish this?

<details>
<summary>Click to answer</summary>

- [x] Amazon DynamoDB.   

</details>

0.   Amazon DynamoDB.

1.   Amazon EC2.

2.   AWS Lambda.

3.   Amazon RDS.


### While developing an application that runs on Amazon EC2 in an Amazon VPC, a Developer identifies the need for centralized storage of application-level logs. Which AWS service can be used to securely store these logs?

<details>
<summary>Click to answer</summary>

- [x] Amazon CloudWatch Logs.   

</details>

0.   Amazon EC2 VPC Flow Logs.

1.   Amazon CloudWatch Logs.

2.   Amazon CloudSearch.

3.   AWS CloudTrail


### A stock market monitoring application uses Amazon Kinesis for data ingestion. During simulated tests of peak data rates, the Kinesis stream cannot keep up with the incoming data. What step will allow Kinesis to accommodate the traffic during peak hours?

<details>
<summary>Click to answer</summary>

- [x] Install the Kinesis Producer Library (KPL) for ingesting data into the stream.   

</details>

0.   Install the Kinesis Producer Library (KPL) for ingesting data into the stream.

1.   Reduce the data retention period to allow for more data ingestion using. DecreaseStreamRetentionPeriod.

2.   Increase the shard count of the stream using UpdateShardCount.

3.   Ingest multiple records into the stream in a single call using PutRecords.


### A company has an AWS CloudFormation template that is stored as a single file. The template is able to launch and create a full infrastructure stack. Which best practice would increase the maintainability of the template?

<details>
<summary>Click to answer</summary>

- [x] Use nested stacks for common template patterns.   

</details>

0.   Use nested stacks for common template patterns.

1.   Embed credentials to prevent typos.

2.   Remove mappings to decrease the number of variables.

3.   Use AWS::Include to reference publicly-hosted template files.


### An on-premises application makes repeated calls to store files to Amazon S3. As usage of the application has increased, 'LimitExceeded' errors are being logged. What should be changed to fix this error?

<details>
<summary>Click to answer</summary>

- [x] Implement exponential backoffs in the application.   

</details>

0.   Implement exponential backoffs in the application.

1.   Load balance the application to multiple servers.

2.   Move the application to Amazon EC2.

3.   Add a one second delay to each API call.


### A company caches session information for a web application in an Amazon DynamoDB table. The company wants an automated way to delete old items from the table. What is the simplest way to do this?

<details>
<summary>Click to answer</summary>

- [x] Add an attribute with the expiration time; enable the Time To Live feature based on that attribute.   

</details>

0.   Write a script that deletes old records; schedule the scripts as a cron job on an Amazon EC2 instance.

1.   Add an attribute with the expiration time; enable the Time To Live feature based on that attribute.

2.   Each day, create a new table to hold session data; delete the previous day's table.

3.   Add an attribute with the expiration time; name the attribute ItemExpiration.


### An application is expected to process many files. Each file takes four minutes to process each AWS Lambda invocation. The Lambda function does not return any important data. What is the fastest way to process all the files?

<details>
<summary>Click to answer</summary>

- [x] Make asynchronous Event Lambda invocations and process the files in parallel.   

</details>

0.   First split the files to make them smaller, then process with synchronous RequestResponse Lambda invocations.

1.   Make synchronous RequestResponse Lambda invocations and process the files one by one.

2.   Make asynchronous Event Lambda invocations and process the files in parallel.

3.   First join all the files, then process it all at once with an asynchronous Event Lambda invocation.


### The upload of a 15 GB object to Amazon S3 fails. The error message reads: 'Your proposed upload exceeds the maximum allowed object size.' What technique will allow the Developer to upload this object?

<details>
<summary>Click to answer</summary>

- [x] Upload the object using the multi-part upload API.   

</details>

0.   Upload the object using the multi-part upload API.

1.   Upload the object over an AWS Direct Connect connection.

2.   Contact AWS Support to increase the object size limit.

3.   Upload the object to another AWS region.


### AWS CodeBuild builds code for an application, creates the Docker image, pushes the image to Amazon Elastic Container Registry (Amazon ECR), and tags the image with a unique identifier. If the Developers already have AWS CLI configured on their workstations, how can the Docker images be pulled to the workstations?

<details>
<summary>Click to answer</summary>

- [x] Run the output of the following:aws ecr get-login and then run: docker pull REPOSITORY URI : TAG.   

</details>

0.   Run the following:docker pull REPOSITORY URI : TAG.

1.   Run the output of the following:aws ecr get-login and then run: docker pull REPOSITORY URI : TAG.

2.   Run the following:aws ecr get-login and then run: docker pull REPOSITORY URI : TAG.

3.   Run the output of the following: aws ecr get-download-url-for-layer and then run: docker pull REPOSITORY URI : TAG.


### A web application is designed to allow new users to create accounts using their email addresses. The application will store attributes for each user, and is expecting millions of user to sign up. What should the Developer implement to achieve the design goals?

<details>
<summary>Click to answer</summary>

- [x] Amazon Cognito user pools.   

</details>

0.   Amazon Cognito user pools.

1.   AWS Mobile Hub user data storage.

2.   Amazon Cognito Sync.

3.   AWS Mobile Hub cloud logic.


### A company needs a new REST API that can return information about the contents of an Amazon S3 bucket, such as a count of the objects stored in it. The company has decided that the new API should be written as a microservice using AWS Lambda and Amazon API Gateway. How should the Developer ensure that the microservice has the necessary access to the Amazon S3 bucket, while adhering to security best practices?

<details>
<summary>Click to answer</summary>

- [x] Create an Amazon S3 bucket policy that specifies the Lambda service as its principal and assign it to the Amazon S3 bucket.   

</details>

0.   Create an IAM user that has permissions to access the Amazon S3 bucket, and store the IAM user credentials in the Lambda function source code.

1.   Create an IAM role that has permissions to access the Amazon S3 bucket and assign it to the Lambda function as its execution role.

2.   Create an Amazon S3 bucket policy that specifies the Lambda service as its principal and assign it to the Amazon S3 bucket.

3.   Create an IAM role, attach the AmazonS3FullAccess managed policy to it, and assign the role to the Lambda function as its execution role.


### An organization is using Amazon CloudFront to ensure that its users experience low-latency access to its web application. The organization has identified a need to encrypt all traffic between users and CloudFront, and all traffic between CloudFront and the web application. How can these requirements be met? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Set the Origin's HTTP Port to 443.
- [x] Set the Viewer Protocol Policy to 'HTTPS Only' or 'Redirect HTTP to HTTPS'.   

</details>

0.   Use AWS KMS to encrypt traffic between CloudFront and the web application.

1.   Set the Origin Protocol Policy to 'HTTPS Only'.

2.   Set the Origin's HTTP Port to 443.

3.   Set the Viewer Protocol Policy to 'HTTPS Only' or 'Redirect HTTP to HTTPS'.

4.   Enable the CloudFront option Restrict Viewer Access.


### An application is using Amazon DynamoDB as its data store, and should be able to read 100 items per second as strongly consistent reads. Each item is 5 KB in size. To what value should the table's provisioned read throughput be set?

<details>
<summary>Click to answer</summary>

- [x] 200 read capacity units.   

</details>

0.   50 read capacity units.

1.   100 read capacity units.

2.   200 read capacity units.

3.   500 read capacity units.


### An application uses Lambda functions to extract metadata from files uploaded to an S3 bucket; the metadata is stored in Amazon DynamoDB. The application starts behaving unexpectedly, and the Developer wants to examine the logs of the Lambda function code for errors. Based on this system configuration, where would the Developer find the logs?

<details>
<summary>Click to answer</summary>

- [x] Amazon CloudWatch.   

</details>

0.   Amazon S3.

1.   AWS CloudTrail.

2.   Amazon CloudWatch.

3.   Amazon DynamoDB


### A Developer is creating a Lambda function that will generate and export a file. The function requires 100 MB of temporary storage for temporary files while executing. These files will not be needed after the function is complete. How can the Developer MOST efficiently handle the temporary files?

<details>
<summary>Click to answer</summary>

- [x] Store the files in the /tmp directory and delete the files at the end of the Lambda function.   

</details>

0.   Store the files in EBS and delete the files at the end of the Lambda function.

1.   Copy the files to EFS and delete the files at the end of the Lambda function.

2.   Store the files in the /tmp directory and delete the files at the end of the Lambda function.

3.   Copy the files to an S3 bucket with a lifecycle policy to delete the files.


### A Developer has developed a web application and wants to deploy it quickly on a Tomcat server on AWS. The Developer wants to avoid having to manage the underlying infrastructure. What is the easiest way to deploy the application, based on these requirements?

<details>
<summary>Click to answer</summary>

- [x] AWS Elastic Beanstalk.   

</details>

0.   AWS CloudFormation.

1.   AWS Elastic Beanstalk.

2.   Amazon S3.

3.   AWS CodePipeline


### An application runs on multiple EC2 instances behind an ELB. Where is the session data best written so that it can be served reliably across multiple requests?

<details>
<summary>Click to answer</summary>

- [x] Write data to Amazon ElastiCache.   

</details>

0.   Write data to Amazon ElastiCache.

1.   Write data to Amazon Elastic Block Store.

2.   Write data to Amazon EC2 Instance Store.

3.   Write data to the root filesystem.


### A company is migrating from a monolithic architecture to a microservices-based architecture. The Developers need to refactor the application so that the many microservices can asynchronously communicate with each other without impacting performance. Use of which managed AWS services will enable asynchronous message passing? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Amazon SQS.
- [x] Amazon SNS.   

</details>

0.   Amazon SQS.

1.   Amazon Cognito.

2.   Amazon Kinesis.

3.   Amazon SNS.

4.   Amazon ElastiCache


### According to best practice, how should access keys be managed in AWS? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Delete all access keys for the account root user.
- [x] Use Amazon IAM roles instead of access keys where possible.   

</details>

0.   Use the same access key in all applications for consistency.

1.   Delete all access keys for the account root user.

2.   Leave unused access keys in the account for tracking purposes.

3.   Embed and encrypt access keys in code for continuous deployment.

4.   Use Amazon IAM roles instead of access keys where possible.


### An application running on an Amazon Linux EC2 instance needs to manage the AWS infrastructure. How can the EC2 instance be configured to make AWS API calls securely?

<details>
<summary>Click to answer</summary>

- [x] Specify a role for the EC2 instance with the necessary privileges.   

</details>

0.   Sign the AWS CLI command using the signature version 4 process.

1.   Run the aws configure AWS CLI command and specify the access key id and secret access key.

2.   Specify a role for the EC2 instance with the necessary privileges.

3.   Pass the access key id and secret access key as parameters for each AWS CLI command.


### An application needs to use the IP address of the client in its processing. The application has been moved into AWS and has been placed behind an Application Load Balancer (ALB). However, all the client IP addresses now appear to be the same. The application must maintain the ability to scale horizontally. Based on this scenario, what is the MOST cost-effective solution to this problem?

<details>
<summary>Click to answer</summary>

- [x] Alter the application code to inspect the X-Forwarded-For header. Ensure that the code can work properly if a list of IP addresses is passed in the header.   

</details>

0.   Remove the application from the ALB. Delete the ALB and change Amazon Route 53 to direct traffic to the instance running the application.

1.   Remove the application from the ALB. Create a Classic Load Balancer in its place. Direct traffic to the application using the HTTP protocol.

2.   Alter the application code to inspect the X-Forwarded-For header. Ensure that the code can work properly if a list of IP addresses is passed in the header.

3.   Alter the application code to inspect a custom header. Alter the client code to pass the IP address in the custom header.


### A development team is using AWS Elastic Beanstalk to deploy a two-tier application that consists of a load-balanced web tier and an Amazon RDS database tier in production. The team would like to separate the RDS instance from the Elastic Beanstalk. How can this be accomplished?

<details>
<summary>Click to answer</summary>

- [x] Change the deployment policy to disassociate the database.   

</details>

0.   Use the Elastic Beanstalk CLI to disassociate the database.

1.   Use the AWS CLI to disassociate the database.

2.   Change the deployment policy to disassociate the database.

3.   Recreate a new Elastic Beanstalk environment without Amazon RDS.


### A company is using AWS CodePipeline to deliver one of its applications. The delivery pipeline is triggered by changes to the master branch of an AWS CodeCommit repository and uses AWS CodeBuild to implement the test and build stages of the process and AWS CodeDeploy to deploy the application. The pipeline has been operating successfully for several months and there have been no modifications. Following a recent change to the application's source code, AWS CodeDeploy has not deployed the updates application as expected. What are the possible causes? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] One of the earlier stages in the pipeline failed and the pipeline has terminated.
- [x] One of the Amazon EC2 instances in the company's AWS CodePipeline cluster is inactive.   

</details>

0.   The change was not made in the master branch of the AWS CodeCommit repository.

1.   One of the earlier stages in the pipeline failed and the pipeline has terminated.

2.   One of the Amazon EC2 instances in the company's AWS CodePipeline cluster is inactive.

3.   The AWS CodePipeline is incorrectly configured and is not executing AWS CodeDeploy.

4.   AWS CodePipeline does not have permissions to access AWS CodeCommit.


### A social media company is using Amazon Cognito in order to synchronize profiles across different mobile devices, to enable end users to have a seamless experience. Which of the following configurations can be used to silently notify users whenever an update is available on all other devices?

<details>
<summary>Click to answer</summary>

- [x] Use an Amazon Cognito stream to analyze the data and push the notifications.   

</details>

0.   Modify the user pool to include all the devices which keep them in sync.

1.   Use the SyncCallback interface to receive notifications on the application.

2.   Use an Amazon Cognito stream to analyze the data and push the notifications.

3.   Use the push synchronization feature with the appropriate IAM role.


### An on-premises application is implemented using a Linux, Apache, MySQL and PHP (LAMP) stack. The Developer wants to run this application in AWS. Which of the following sets of AWS services can be used to run this stack?

<details>
<summary>Click to answer</summary>

- [x] Amazon EC2, Amazon Aurora.   

</details>

0.   Amazon API Gateway, Amazon S3.

1.   AWS Lambda, Amazon DynamoDB.

2.   Amazon EC2, Amazon Aurora.

3.   Amazon Cognito, Amazon RDS.

4.   Amazon ECS, Amazon EBS.


### An application displays a status dashboard. The status is updated by 1 KB messages from an SQS queue. Although the status changes infrequently, the Developer must minimize the time between the message arrival in the queue and the dashboard update. What technique provides the shortest delay in updating the dashboard?

<details>
<summary>Click to answer</summary>

- [x] Retrieve the messages from the queue using long polling every 20 seconds.   

</details>

0.   Retrieve the messages from the queue using long polling every 20 seconds.

1.   Reduce the size of the messages by compressing them before sending.

2.   Retrieve the messages from the queue using short polling every 10 seconds.

3.   Reduce the size of each message payload by sending it in two parts.


### An on-premises legacy application is caching data files locally and writing shared images to local disks. What is necessary to allow for horizontal scaling when migrating the application to AWS?

<details>
<summary>Click to answer</summary>

- [x] Modify the application to read and write cache data on Amazon S3, and also store shared images on S3.   

</details>

0.   Modify the application to have both shared images and caching data written to Amazon EBS.

1.   Modify the application to read and write cache data on Amazon S3, and also store shared images on S3.

2.   Modify the application to use Amazon S3 for serving shared images; cache data can then be written to local disks.

3.   Modify the application to read and write cache data on Amazon S3, while continuing to write shared images to local disks.


### A Developer must trigger an AWS Lambda function based on the item lifecycle activity in an Amazon DynamoDB table. How can the Developer create the solution?

<details>
<summary>Click to answer</summary>

- [x] Enable a DynamoDB stream, and trigger the Lambda function synchronously from the stream.   

</details>

0.   A Developer must trigger an AWS Lambda function based on the item lifecycle activity in an Amazon DynamoDB table. How can the Developer create the solution?

1.   Enable a DynamoDB stream that publishes an SNS message. Trigger the Lambda function asynchronously from the SNS message.

2.   Enable a DynamoDB stream, and trigger the Lambda function synchronously from the stream.

3.   Enable a DynamoDB stream, and trigger the Lambda function asynchronously from the stream.


### After installing the AWS CLI, a Developer tries to run the command awsconfigure but receives the following error:Error: aws: command not found. What is the most likely cause of this error?

<details>
<summary>Click to answer</summary>

- [x] The aws executable is not in the PATH environment variable.   

</details>

0.   The aws executable is not in the PATH environment variable.

1.   Access to the aws executable has been denied to the installer.

2.   Incorrect AWS credentials were provided.

3.   The aws script does not have an executable file mode.


### The Developer for a retail company must integrate a fraud detection solution into the order processing solution. The fraud detection solution takes between ten and thirty minutes to verify an order. At peak, the web site can receive one hundred orders per minute. What is the most scalable method to add the fraud detection solution to the order processing pipeline?

<details>
<summary>Click to answer</summary>

- [x] Add all new orders to an SQS queue. Configure an Auto Scaling group that uses the queue depth metric as its unit of scale to launch a dynamically-sized fleet of EC2 instances spanning multiple AZs with the fraud detection solution installed on them to pull orders from this queue. Update the order with a pass or fails status.   

</details>

0.   Add all new orders to an Amazon SQS queue. Configure a fleet of 10 EC2 instances spanning multiple AZs with the fraud detection solution installed on them to pull orders from this queue. Update the order with a pass or fails status.

1.   Add all new orders to an SQS queue. Configure an Auto Scaling group that uses the queue depth metric as its unit of scale to launch a dynamically-sized fleet of EC2 instances spanning multiple AZs with the fraud detection solution installed on them to pull orders from this queue. Update the order with a pass or fails status.

2.   Add all new orders to an Amazon Kinesis Stream. Subscribe a Lambda function to automatically read batches of records from the Kinesis Stream. The Lambda function includes the fraud detection software and will update the order with a pass or fail status.

3.   Write all new orders to Amazon DynamoDB. Configure DynamoDB Streams to include all new orders. Subscribe a Lambda function to automatically read batches of records from the Kinesis Stream. The Lambda function includes the fraud detection software and will update the order with a pass or fail status.


### When a Developer tries to run an AWS CodeBuild project, it raises an error because the length of all environment variables exceeds the limit for the combined maximum of characters. What is the recommended solution?

<details>
<summary>Click to answer</summary>

- [x] Use AWS Systems Manager Parameter Store to store large numbers of environment variables.   

</details>

0.   Add the export LC_ALL="en_US.utf8" command to the pre_build section to ensure POSIX localization.

1.   Use Amazon Cognito to store key-value pairs for large numbers of environment variables.

2.   Update the settings for the build project to use an Amazon S3 bucket for large numbers of environment variables.

3.   Use AWS Systems Manager Parameter Store to store large numbers of environment variables.


### A set of APIs are exposed to customers using the Amazon API Gateway. These APIs have caching enabled on the API Gateway. Customers have asked for an option to invalidate this cache for each of the APIs. What action can be taken to allow API customers to invalidate the API Cache?

<details>
<summary>Click to answer</summary>

- [x] Ask customers to pass an HTTP header called Cache-Control:max-age=0.   

</details>

0.   Ask customers to use AWS credentials to call the InvalidateCache API.

1.   Ask customers to invoke an AWS API endpoint which invalidates the cache.

2.   Ask customers to pass an HTTP header called Cache-Control:max-age=0.

3.   Ask customers to add a query string parameter called 'INVALIDATE_CACHE' when making an API call.


### A Developer has been asked to build a real-time dashboard web application to visualize the key prefixes and storage size of objects in Amazon S3 buckets. Amazon DynamoDB will be used to store the Amazon S3 metadata. What is the optimal and MOST cost-effective design to ensure that the real-time dashboard is kept up to date with the state of the objects in the Amazon S3 buckets?

<details>
<summary>Click to answer</summary>

- [x] Use an Amazon CloudWatch event backed by an AWS Lambda function. Issue an Amazon S3 API call to get a list of all Amazon S3 objects and persist the metadata within DynamoDB. Have the web application poll the DynamoDBtable to reflect this change.   

</details>

0.   Use an Amazon CloudWatch event backed by an AWS Lambda function. Issue an Amazon S3 API call to get a list of all Amazon S3 objects and persist the metadata within DynamoDB. Have the web application poll the DynamoDBtable to reflect this change.

1.   Use Amazon S3 Event Notification backed by a Lambda function to persist the metadata into DynamoDB. Have the web application poll the DynamoDB table to reflect this change.

2.   Run a cron job within an Amazon EC2 instance to list all objects within Amazon S3 and persist the metadata into DynamoDB. Have the web application poll the DynamoDB table to reflect this change.

3.   Create a new Amazon EMR cluster to get all the metadata about Amazon S3 objects; persist the metadata into DynamoDB. Have the web application poll the DynamoDB table to reflect this change.


### A Developer must repeatedly and consistently deploy a serverless RESTful API on AWS. Which techniques will work? (Choose TWO)

<details>
<summary>Click to answer</summary>

- [x] Deploy a SAM template with an inline Swagger definition.
- [x] Define a Swagger file. Deploy a SAM template that references the Swagger file.   

</details>

0.   Define a Swagger file. Use AWS Elastic Beanstalk to deploy the Swagger file.

1.   Define a Swagger file. Use AWS CodeDeploy to deploy the Swagger file.

2.   Deploy a SAM template with an inline Swagger definition.

3.   Define a Swagger file. Deploy a SAM template that references the Swagger file.

4.   Define an inline Swagger definition in a Lambda function. Invoke the Lambda function.


### An existing serverless application processes uploaded image files. The process currently uses a single Lambda function that takes an image file, performs the processing, and stores the file in Amazon S3. Users of the application now require thumbnail generation of the images. Users want to avoid any impact to the time it takes to perform the image uploads. How can thumbnail generation be added to the application, meeting user requirements while minimizing changes to existing code?

<details>
<summary>Click to answer</summary>

- [x] Change the existing Lambda function handling the uploads to create thumbnails at the time of upload. Have the function store both the image and thumbnail in Amazon S3.   

</details>

0.   Change the existing Lambda function handling the uploads to create thumbnails at the time of upload. Have the function store both the image and thumbnail in Amazon S3.

1.   Create a second Lambda function that handles thumbnail generation and storage. Change the existing Lambda function to invoke it asynchronously.

2.   Create an S3 event notification with a Lambda function destination. Create a new Lambda function to generate and store thumbnails.

3.   Create an S3 event notification to an SQS Queue. Create a scheduled Lambda function that processes the queue, and generates and stores thumbnails.


### A company is using Amazon API Gateway to manage access to a set of microservices implemented as AWS Lambda functions. Following a bug report, the company makes a minor breaking change to one of the APIs. In order to avoid impacting existing clients when the new API is deployed, the company wants to allow clients six months to migrate from v1 to v2. Which approach should the Developer use to handle this change?

<details>
<summary>Click to answer</summary>

- [x] Use API Gateway to deploy a new stage named v2 to the API and provide users with its URL.   

</details>

0.   Update the underlying Lambda function and provide clients with the new Lambda invocation URL.

1.   Use API Gateway to automatically propagate the change to clients, specifying 180 days in the phased deployment parameter.

2.   Use API Gateway to deploy a new stage named v2 to the API and provide users with its URL.

3.   Update the underlying Lambda function, create an Amazon CloudFront distribution with the updated Lambda function as its origin.


### A company developed a set of APIs that are being served through the Amazon API Gateway. The API calls need to be authenticated based on OpenID identity providers such as Amazon or Facebook. The APIs should allow access based on a custom authorization model. Which is the simplest and MOST secure design to use to build an authentication and authorization model for the APIs?

<details>
<summary>Click to answer</summary>

- [x] Use Amazon Cognito user pools and a custom authorizer to authenticate and authorize users based on JSON Web Tokens.   

</details>

0.   Use Amazon Cognito user pools and a custom authorizer to authenticate and authorize users based on JSON Web Tokens.

1.   Build a OpenID token broker with Amazon and Facebook. Users will authenticate with these identify providers and pass the JSON Web Token to the API to authenticate each API call.

2.   Store user credentials in Amazon DynamoDB and have the application retrieve temporary credentials from AWS STS. Make API calls by passing user credentials to the APIs for authentication and authorization.

3.   Use Amazon RDS to store user credentials and pass them to the APIs for authentications and authorization.


### Where should an Elastic Beanstalk configuration file named healthcheckur1.config be placed in the application source bundle?

<details>
<summary>Click to answer</summary>

- [x] In the .ebextensions folder.   

</details>

0.   In the root of the application.

1.   In the bin folder.

2.   In healthcheckur1.config.ebextension under root.

3.   In the .ebextensions folder.


### A Developer has implemented a Lambda function that needs to add new customers to an RDS database that is expected to run hundreds of times per hour. The Lambda function is configured to use 512MB of RAM and is based on the following pseudo code. After testing the Lambda function, the Developer notices that the Lambda execution time is much longer than expected. What should the Developer do to improve performance?

<details>
<summary>Click to answer</summary>

- [x] Move the database connection and close statement out of the handler. Place the connection in the global space.   

</details>

0.   Increase the amount of RAM allocated to the Lambda function, which will increase the number of threads the Lambda can use.

1.   Increase the size of the RDS database to allow for an increased number of database connections each hour.

2.   Move the database connection and close statement out of the handler. Place the connection in the global space.

3.   Replace RDS wit Amazon DynamoDB to implement control over the number of writes per second.


### A static website is hosted in an Amazon S3 bucket. Several HTML pages on the site use JavaScript to download images from another Amazon S3 bucket. These images are not displayed when users browse the site. What is the possible cause for the issue?

<details>
<summary>Click to answer</summary>

- [x] Cross Origin Resource Sharing must be enabled on the Amazon S3 bucket.   

</details>

0.   The referenced Amazon S3 bucket is in another region.

1.   The images must be stored in the same Amazon S3 bucket.

2.   Port 80 must be opened on the security group in which the Amazon S3 bucket is located.

3.   Cross Origin Resource Sharing must be enabled on the Amazon S3 bucket.


### Amazon S3 has the following structure: S3://BUCKET/FOLDERNAME/FILENAME.zip Which S3 best practice would optimize performance with thousands of PUT request each second to a single bucket?

<details>
<summary>Click to answer</summary>

- [x] Prefix folder names with random hex hashes; for example, s3://BUCKET/23a6-FOLDERNAME/FILENAME.zip.   

</details>

0.   Prefix folder names with user id; for example, s3://BUCKET/2013-FOLDERNAME/FILENAME.zip.

1.   Prefix file names with timestamps; for example, s3://BUCKET/FOLDERNAME/2013-26-05-15-00-00-FILENAME.zip.

2.   Prefix file names with random hex hashes; for example, s3://BUCKET/FOLDERNAME/23a6-FILENAME.zip.

3.   Prefix folder names with random hex hashes; for example, s3://BUCKET/23a6-FOLDERNAME/FILENAME.zip.
