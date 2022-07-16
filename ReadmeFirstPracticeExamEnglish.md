### First Practice Exam (English)
---
You have been asked to set up network security in a virtual private cloud. Your company wants to have multiple subnetworks and limit traffic between the subnetworks. Which network security control would you use to control the flow of traffic between subnets?
- [x] Firewall
---
While working on a project, an application administrator has been given the responsibility of managing all resources. He wants to delegate the responsibility of managing the existing service accounts to another administrator. He will also be responsible to manage the other service accounts that will be created. Which of the following is the best way to delegate the privileges required to manage all the service accounts?
- [x] Granting iam.serviceAccountUser to the administrator at the project level
---
A user prefers services that require minimal setup. Why would you recommend Cloud Storage, App Engine, and Cloud Functions?
- [x] They are serverless.
---
You are deploying a new relational database to support a web application. Which type of storage system would you use to store data files of the database?
- [x] Block storage
---
You have created a virtual machine. Which of the following system administration operations are you allowed to perform on it?
- [x] All of the above
---
If you use a cluster that is managed by a cloud provider, which of these will be managed for you by the cloud provider?
- [x] All of the above
---
Your client’s transactions must access a drive attached to a virtual machine that allows for random access to parts of files. What kind of storage does the attached drive provide?
- [x] Block storage
--- 
Why can cloud providers offer elastic resource allocation?
- [x] Extensive resources and the ability to quickly shift resources between customers enables public cloud providers to offer elastic resource allocation more efficiently than can be done in smaller data centers.
---
Your client wants to develop a new cost-effective web application that runs on a serverless platform using Cloud Function, Cloud Storage, Pub/Sub, and Cloud CDN. The expected data would be 20 GB. Which of the following databases would be the most suitable schemaless option to support the serverless functionality?
- [x] Cloud Firestore
---
Your managers want you to suggest a low-cost storage option that could be used to share read-only data across multiple instances with high performance and no edge caching. Which storage option would you suggest?
- [x] Cloud Storage
---
What is the command for creating a storage bucket that has once per month access and is named “archive_bucket”?
- [x] gsutil mb -c nearline gs://archive_bucket
---
Which of the following commands could be used to change the storage class of an object in Cloud Storage?
- [x] gsutil rewrite -s [STORAGE_CLASS] gs://Reports-PDF/[OBJECT_NAME]
---
You have set a firewall rule that will permit inbound connections to a VM instance named bangkitserver-2. You want to apply this rule only if there is not another rule that would deny that traffic. What priority would you give to this rule?
- [x] 65535
---
You created a Cloud SQL instance with automated backup switched on. After a few weeks your manager asked you to restore a 12 days older snapshot. While restoring the snapshot you notice that there are only 7 automated backups available. What can be the reason?
- [x] CloudSQL only stores 7 automated backups.
---
A bug has been identified within your Python application which is hosted using App Engine and you are about to roll out a new version of the application to resolve the bug, but do not want the traffic to automatically shift to a new version just to make sure the new version does not break anything. How would you achieve it?
- [x] Pass --no-promote flag while deploying a new version.
---
You work for a retail company that has a busy online store. As you are approaching the new year, you find that your e-store is getting more and more traffic. You ensure that your web servers are behind a managed instance group. However, you notice that the web tier is frequently scaling, sometimes multiple times in an hour. You need to keep the instance group from scaling up and down so rapidly. Which of the following options would help you achieve this?
- [x] Increase the cooldown period.
---
Your client is planning to deploy an application on Google App Engine and has a requirement to store 1TB of data in schemaless, strongly consistent, ACID-compliant database solution. Which of the following would you consider for this?
- [x] Google Cloud Datastore
---
You have been asked to automate the infrastructure deployment using Google Deployment Manager service. Which format does the Deployment Manager template support?
- [x] YAML
---
You created a VPC with a CIDR block of 10.40.0.0/16 with 2 subnets of CIDR range 10.40.1.0/24 and 10.40.2.0/24. What would be the default routes within this virtual private connection having the broadest CIDR range?
- [x] 0.0.0.0/0
---
You are working on a project whose development phase has been completed and the manager has asked you to create a new project for UAT environment which should be a clone of the development environment. Dev environment consists of 5 VMs which need to be replicated to UAT environment. How can you achieve this?
- [x] Create a custom image of each instance in the dev environment and while launching VMs in the UAT environment under boot disk select Custom images, select your project and choose the relevant image.
---
You have deployed a Django 1.5 Python application to App Engine. This version of Django requires Python 3. Due to some issues, App Engine is trying to run the application using Python 2. Which of the following files would you check and modify (if required) to ensure that Python 3 is used with the application?
- [x] app.yaml
---
Your client has prepared a new company policy in which each developer must sign a Contributor License Agreement (CLA) before code changes are committed to any version control repository. You have been asked to check each commit in a repository that includes the policy and your manager has also provided you with node.js code. Which of the following services can help you implement this solution?
- [x] Cloud Function
---
One of your team members had accidentally included a service account private JSON key while pushing code to GitHub. What steps should you immediately perform?
- [x] Delete the JSON file from GitHub, remove the key from Google Cloud IAM and generate a new key for use.
---
You want to filter logs present in Stackdriver Log Viewer using more than a simple text filter. Which feature will allow you to do it?
- [x] Advanced Filter
---
You need serverless computing for file processing and running the backend of a website; which two products can you choose from Google Cloud Platform?
- [x] App Engine dan Cloud Functions
---
Your client wants you to share a screenshot of all the deployments that are/were running on your Google Cloud Deployment Manager. Which command will you use to resolve this?
- [x] gcloud deployment-manager deployments list
---
You are working for a healthcare industry and for compliance reasons your manager has asked you to make sure that all logs are maintained for a minimum of 6 years. Which service can be used and is supported by Stackdriver Logging?
- [x] BigQuery & GCS
---
What is the unit per minute cost of a virtual server based on?
- [x] The characteristics of the server
---
When setting up a network in GCP, what is your network and the resources in it treated as?
- [x] Virtual private cloud
---
Being a Senior Cloud Engineer of the company, you are asked to launch a managed MySQL DB using custom VPC with network range of 172.17.0.0/16 on Google Cloud keeping security at utmost priority allowing team members to access it only over a private channel.You completed the setup with all the requirements, but developers are unable to access DB over the private network via application hosted on VM. What can be the reason?
- [x] You did not whitelist 172.17.0.0/16 in the firewall.
---
You have been hired as a contractor by one of the travel technology companies that is planning to containerize their existing applications in such a way that they can perform a lift and shift very easily in the future if they plan to move away from Google Cloud. Which service will best suit this case?
- [x] Kubernetes Engine
---
What is the gcloud command to create a cluster named ch09-cluster10 with four nodes?
- [x] gcloud container clusters create ch09-cluster10 --num-nodes=4
---
You are a Google Cloud Engineer and assigned to set up a project for the team of four members. You need to grant only general permissions for all the resources of the project. You decided to grant a primitive role to each person for different levels of access based on their responsibilities in the project. What is not considered as a primitive role in the Google Cloud Platform console?
- [x] Publisher
---
You created an application for a large hospital which stores around 1 GB of files every day on GCS. Most of these files are accessed very rarely after six months from the day of the first upload but are important and cannot be deleted. Which storage class would you prefer to save money after 6 months?
- [x] Nearline
---
You have an application server running on Compute Engine in the europe-west1-d zone. You need to ensure high availability and replicate the server to the europe-west2-c zone using the fewest steps possible. What should you do?
- [x] Create a snapshot from the disk. Create a disk from the snapshot in the europe-west2-c zone. Create a new VM with that disk.
---
Your client has prepared a new company policy in which each developer must sign a Contributor License Agreement (CLA) before code changes are committed to any version control repository. You have been asked to check each commit in a repository that includes the policy and your manager has also provided you with node.js code. Which of the following services can help you implement this solution?
- [x] Cloud Function
---
Your client has a web application that is currently using a single GCE to read the messages from a pub/sub topic, process them and store them in Cloud Bigtable by its unique order id. When a user uploads an order to Cloud Storage, it triggers a Cloud Function that inserts a message to pub/subtopic. The traffic is expected to increase next week and as a cloud engineer, you are expected to resolve any possible auto scaling problem. Which service is not likely to auto scale when the traffic is increased?
- [x] Google Cloud Engine
---
You’re working for a company as a cloud engineer. You have a managed instance group for which the autoscaling is enabled if CPU utilization is 70%. Right now there are 4 instances available in this instance group. When you connect to one of the instances, you see that the CPU utilization is 75% and no new instance is started in the group. What could be the possible reason for not starting another instance here?
- [x] The average CPU usage of the instance group is less than 70%
---
One of your clients has asked you to create an SFTP server on Google Cloud. Which storage service of Google Cloud will be the most reliable and durable option?
- Firestore
- vm
---
A new junior engineer is joining your team. Your manager asks you to create an IAM user for him. You are trying to create an IAM user for the new joiner, but you receive an error saying: “Email addresses and domains must be associated with an active Google Account or Google Apps Account”. What is the possible reason for this?
- [x] He does not have a GSuite account or an account with the Identity Platform your organization has linked to Google Cloud for authentication purposes.
---
A VM instance is trying to read from a Cloud Storage bucket. Reading the bucket is allowed by IAM  roles granted to the service account of the VM. Reading buckets is denied by the scopes assigned to the VM. What will happen if the VM tries to read from the bucket?
- [x] The read will not execute because both scopes and IAM roles are applied to determine what operations can be performed.
---
You are appointed as a head of infrastructure security and the first thing you are asked is to create few IAM users following best security practices. How would you ensure that these users are only able to launch a new instance and list them?
- [x] Create a custom role with specific permissions and attach it to users.
---
Which is the correct command to bind an IAM policy to a service account at an organization or folder level?
- [x] gcloud organizations add-iam-policy-binding org_id --member serviceAccount:dicoding@dicoding-prj.iam.gserviceaccount.com --role roles/viewer
---
Someone from a different team has approached you that he is working on a web application hosted on Google Cloud VM which needs to view access to Google Cloud Storage service. Which of the following is the best approach?
- [x] VM Instances by default have read access to Google Cloud Storage service, so nothing needs to be done.
---
John is assigned a new devops project in GCP and he needs deploymentmanager.deployments.* permission to make use of Deployment Manager service. Which of the following roles would you create for him?
- [x] Deployment Manager Custom
---
You want to filter logs present in Stackdriver Log Viewer using more than a simple text filter. Which feature will allow you to do it?
- [x] Advanced Filter
---
You are working along with a team of developers who are building an accounting application for a startup. Until now, they were using VM disk to store logs but have now realized that this strategy is not scalable and want a different solution to store logs. Which service would you recommend to the team?
- Flow logs
---
You are building up an application for your client which has API, Web, App and DB layer. The client has asked you to decouple the application so that each request is successfully acknowledged and processed by the application layer. Which service will you use for the same?
- [x] Pub/Sub
---
Which of the following commands is used to create buckets in Cloud Storage?
- gcloud storage buckets create
---
A medical clinic has a retention policy of 5 years. The records older than 4 months get accessed a few times in each quarter for reporting purposes. The clinic is using Cloud Storage to store all their records and is looking for a cost-effective archiving solution. Which object lifecycle management option would you recommend to the clinic authorities?
- Condition: creationDate:20171231 action:type:SetStorageClass, storageClass: NEARLINE
---
You are working for a service company that has an automobile client. The client has developed an application for internal use with Erlang and has approached your company to help him to ease the application deployment process on Google Cloud. The company does not have highly trained people, so it wants you to deploy the application in such a way that post-deployment, they will be able to manage it without worrying about the infrastructure. Which of the following services would you prefer?
- Google Kubernetes Engine
---
Your client has a web application that is currently using a single GCE to read the messages from a pub/sub topic, process them and store them in Cloud Bigtable by its unique order id. When a user uploads an order to Cloud Storage, it triggers a Cloud Function that inserts a message to pub/subtopic. The traffic is expected to increase next week and as a cloud engineer, you are expected to resolve any possible auto scaling problem. Which service is not likely to auto scale when the traffic is increased?
- [x] Google Cloud Engine
---
A team of developers has been working on a Java 8 application on their local machine but the company has now decided to create Windows VM for the team and let them work on VM instead of working on a local machine. Additionally, your manager has asked to send all stack traces to a common place. Which service would you use to meet the following requirement?
- [x] Cloud Trace
---
Your application servers are deployed in a private subnet and you connect to an application instance using a bastion host, you connect to the bastion host using Console Shell and then ssh to the respective application instance. Unfortunately, Cloud Shell is taking a lot of time to respond and your manager wants you to ssh to the instance to fix an application specific configuration. What command would you use to SSH into the server from the public end?
- [x] gcloud compute ssh username@bastion-host
---
PT Bangkit has deployed an application using Google App Engine standard environment. You have been asked to update the cron schedules and default cookie expiration time, which of the following predefined roles has access to update default cookie expiration but no access to update cron schedules?
- [x] App Engine Admin
---
Someone from a different team has approached you that he is working on a web application hosted on Google Cloud VM which needs to view access to Google Cloud Storage service. Which of the following is the best approach?
- [x] VM Instances by default have read access to Google Cloud Storage service, so nothing needs to be done.
---
Your client hosts a static website on Cloud Storage written in HTML, CSS, JavaScript. The site targets users in North America, the usage of the website has grown worldwide and hundreds of thousands of visitors access it monthly. Visitors from different parts of the world are experiencing slow performance due to latency while users in the United States experience normal response times. What service can mitigate this issue?
- Load Balancer
---
What is the gcloud command to set default zone for compute engine server using gcloud CLI?
- [x] gcloud config set compute/zone us-east1-a
---
You created a bucket in cloud storage and uploaded some files and then enabled object versioning on it. Which version the files you have already added will have?
- [x] Null
---
You have been hired as a contractor by one of the travel technology companies that is planning to containerize their existing applications in such a way that they can perform a lift and shift very easily in the future if they plan to move away from Google Cloud. Which service will best suit this case?
- [x] Kubernetes Engine
---
Being a Senior Cloud Engineer of the company, you are asked to launch a managed MySQL DB using custom VPC with network range of 172.17.0.0/16 on Google Cloud keeping security at utmost priority allowing team members to access it only over a private channel. You completed the setup with all the requirements, but developers are unable to access DB over the private network via application hosted on VM. What can be the reason?
- [x] You did not whitelist 172.17.0.0/16 in the firewall.
---
Which command will let you enable Google Compute service using gcloud CLI?
- gcloud service compute enable
- gcloud service enable compute
---
You are working for a genomics company in the US that is planning to conduct data analysis on around 10 TB of data. The company would require 20 vCPUs and 60GB of RAM for the same. You have been asked to figure out the cheapest option to conduct the analysis. Which of the following would you use?
- [x] Preemptible instances
---
Your program manager wants you to set up a hybrid network between your Google Cloud and on-premise infrastructure that allows high bandwidth, low latency connection between both the networks. As a Sr. Cloud Engineer, which one of the following services will you select?
- [x] Interconnect
---
Engineering team is building an application which routes requests on the TCP layer. They need a load balancer with support of SSL termination on load balancer. Which of the following is the best available option?
- [x] SSL Proxy Load Balancer
---
Your team is building a media collection and analysis application for one of your clients. They have asked you to enable Google Photos API and YouTube API. Moreover, they want to test the API without integrating it within the application. Which service would help your development team test the API without integration?
- API Library
- Marketplace Explorer
---
You are working for a service company that has an automobile client. The client has developed an application for internal use with Erlang and has approached your company to help him to ease the application deployment process on Google Cloud. The company does not have highly trained people, so it wants you to deploy the application in such a way that post-deployment, they will be able to manage it without worrying about the infrastructure. Which of the following services would you prefer?
- [x] App Engine Flexible
---
You are planning to build a microservice application with docker containers and want to host them on Google Cloud as stateless and serverless. Which service will help you serve the need?
- [x] Cloud Run
---
Your engineering team has developed an application which will be deployed using GKE. The application needs a monitoring agent running on each node without fail and any change in the number of nodes should also update the count of the monitoring agent. Which API resource would you use to achieve the desired result?
- [x] DaemonSet
---
You were inspecting the containers on a VM and found out that a pod is running which is no more required. You try to delete it but every time a new pod is created. What do you need to delete now for removing that pod?
- [x] ReplicaSet
---
You have a website hosted on a Compute Engine VM. Users can access the website using the domain name you provided. You do some maintenance work on the VM and stop the server and restart it. Now users cannot access the website. No other changes have occurred on the subnet. What might be the cause of the problem?
- You do not have enough addresses available on your subnet.
- The restart caused a change in the DNS record.
---
A team of developers has been working on a Java 8 application on their local machine but the company has now decided to create Windows VM for the team and let them work on VM instead of working on a local machine. Additionally, your manager has asked to send all stack traces to a common place. Which service would you use to meet the following requirement?
- [x] Cloud Trace
---
You have an application running on Google Cloud VM written in C#.Net for the last few weeks. Suddenly you experience elevated latency and poor performance among application endpoints. Which service can help you troubleshoot this issue?
- [x] Stackdriver Trace
---
Your client wants to migrate their 30 TB of Hadoop or Spark cluster from an RHEL 6.5 on-premise server to Google Cloud Platform. Which of the following services can be used at the GCP end?
- [x] Dataproc
---
You are working as a system administrator and have been asked to make sure that all images are patched up to date and developers are not allowed to use old images that are not up to date as per PCI compliance. How would you achieve this?
- Mark image as deprecated to prevent users from using the old image.
- Drop a mail to all the developers regarding which image to use whenever you patch images.
---
You deployed 10 microservices using Google Kubernetes Engine. The command kubectl run deployed the microservices in different pods, 2 weeks later your manager asked you to delete the pods as the services were no longer needed. Which of the following options is the best way to delete the pods?
- [x] kubectl delete deployments/<name> services/<name>
---
Your company has purchased a threat detection service from a third party and has asked you to upload all network logs to the application. Which of the following service will meet your requirements?
- Flow Logs
---
A new junior engineer is joining your team. Your manager asks you to create an IAM user for him. You are trying to create an IAM user for the new joiner, but you receive an error saying: “Email addresses and domains must be associated with an active Google Account or Google Apps Account”. What is the possible reason for this?
- You need to ask the new joiner to attach permission to his GSuite account to allow you to create an IAM user.
- You do not have permission to create new IAM users.
---
Which is the correct command to bind an IAM policy to a service account at an organization or folder level?
- [x] gcloud organizations add-iam-policy-binding org_id --member serviceAccount:dicoding@dicoding-prj.iam.gserviceaccount.com --role roles/viewer
----
PT Bangkit has deployed an application using Google App Engine standard environment. You have been asked to update the cron schedules and default cookie expiration time, which of the following predefined roles has access to update default cookie expiration but no access to update cron schedules?
- Storage Caching
---
Your client wants you to update a viewer role in your google cloud platform project using CLI. The roles have access to the App Engine list and get method and you have been asked to add the cloud storage list and get permissions. The changes were reflected after you ran the command but the user complained that they are unable to view the content of Cloud Storage buckets using CLI. What could be the most appropriate reason?
- Cloud Storage permission needs to be created and attached separately.
- The App Engine permission in the roles is overlapping the new permissions.
---
You want to list permissions in a role using Cloud Console. Where would you go to see that?
- IAM & Admin; select Roles. All permissions will be displayed.
- IAM & Admin; select Audit Logs.
