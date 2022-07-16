---
A startup has reached out to you for help with their single page application which they will be running using docker. They want you to suggest the best possible service which can be used by the developers to deploy and manage the application on their own. Which one according to you will be best suited for their requirement without considering the management of underlying infrastructure?
- Cloud Engine
---
You have recently joined a startup and have been asked to create a new Google Cloud account for the company along with setting up budget alarm of $100. You have set up an alarm with 40%, 60%, 90%, and 100% threshold. What will happen once the threshold of 100% is reached?
- All VMs will be stopped so that you don’t exceed your budget.
---
What file system technology is Cloud Filestore based on?
- [x] Network File System (NFS)
---
As a cloud engineer, you have been asked to upgrade the free trial of your account and rename it to a production-inventory-system. You are getting permission denied error while making the changes. Which of the following permissions will solve the problem?
- [x] billing.accounts.update
---
You have recently joined a startup and have been asked to create a new Google Cloud account for the company along with setting up budget alarm of $100. You have set up an alarm with 40%, 60%, 90%, and 100% threshold. What will happen once the threshold of 100% is reached?
- Network File System
---
Investing in servers for extended periods of time, such as committing to use servers for three to five years, works well when?
- [x] A company can accurately predict server need for an extended period of time
---
You have to run several services to support an application. Which of the following is a good deployment model?
- Use a small VM for all services and increase the size of the VM when CPU utilization exceeds 90 percent
---
You’ve been advised by a colleague to use a cache with your database application to address one of several issues with your application. How will this affect your application?
- [x] Using a cache will reduce latency, since retrieving from a cache is faster than retrieving from SSDs or HDDs
---
Your company has replaced your laptop OS from Windows to Ubuntu and you installed a stable release of Cloud SDK on your machine, however when you run kubectl, you receive an error stating “Command ‘kubectl’ not found”. Which command will you use to install kubectl on Ubuntu?
- sudo yum install kubectl
---
You plan to use Cloud Vision to analyze images and extract text seen in the image. You plan to process between 1000 and 2500 images per hour. How many virtual machines should you allocate to meet peak demand?
- 10
---
A cloud engineer wants to create a VM named my-server-1 with four CPUs. Which of the following commands would he use to create the VM my-server-1?
- gcloud compute instances create --machine-type=n1-standard-4 --instancename my-server-1
---
A new client has approached your company with a requirement that they want to host a serverless on Google Cloud, but before that want you to give them a price estimate of running a serverless application using Cloud Function. Which all parameters will you consider while calculating price using Google Pricing Calculator?
- [x] Type, Bandwidth, Execution Time & Invocations.
---
You created a Nearline bucket in GCS by using the default parameters, after an hour you realized the requirement was to create a Nearline bucket in asia-south1 location. How will you correct this configuration change?
- Modify the bucket and change its storage class to regional and choose the location to asia-south1.
---
You are starting to work on a client’s project who is looking for a database service within Google Cloud that is horizontally scalable, supports gigabyte size of relational data, and even supports ACID for reliable storage of data. Which service will you recommend?
- BigQuery
---
You want your application hosted on a VM to fetch metadata of that instance. Which command will help you to fetch it?
- curl <instance-private-ip>/metadata/v1/
---
Your client wants to migrate an application to Google Cloud which has 15 TB of relational data. The database is growing rapidly by 10 GB every day. In addition, to support the traffic, at least 10 read replicas are required. Which of the following services would you meet the requirements?
- Cloud Bigtable
---
You have 100 TB of non-relational data and want to run analytics on it to see the previous year’s net sales. Which tool suits your requirement?
- GCS
---
Your inventory application has 2 backend API servers launched using Auto Scaling Groups, you have been asked to load balance UDP, TCP, and SSL traffic on ports that are not supported by the TCP proxy and SSL proxy load balancer. Which of the following Load Balancers would you use?
- HTTP(S) Load Balancer
---
You have been asked to build a backend using Clojure and host it on Google Cloud with full freedom of choosing OS, applications, libraries, etc. Which service will you prefer?
- App Engine Standard
---
You are hired by an oil company that wants you to lead the migration of Oracle DB and DB2 to Google Cloud. Which of the following is the best option?
- [x] VM for both Oracle and DB2
---
A developer accidentally deleted some of the files from a bucket. Luckily, the files were not critical and were re-created soon. Because of this, your team lead has asked you to enable versioning on the bucket. Which command would help you enable the same?
- gsutil gs://documents-bucket enable versioning
---
Which of the following export options are available with Google Cloud Billing?
- [x] BigQuery & File
---
You have been asked to deploy a highly available Kubernetes cluster using Google Kubernetes Engine by your manager. While spinning up the cluster you realize you do not see an option of creating a master. What can be the reason?
- GKE does not use master nodes to control child nodes.
---
You have created a subnet named subnetace1 with 16.382 addresses using 192.168.0.0. Later you realize that you won’t require too many addresses, and so you want to reduce addresses to 254. Which of the following commands would you use?
- [x] There is no command in google cloud to reduce the number of available addresses in a subnet.
---
You need to deploy an update to an application in Google App Engine. The update is risky, but it can only be tested in a live environment. What is the best way to introduce the update to minimize risk?
- [x] Deploy a new version of the application but use traffic splitting to only direct a small number of users to the new version.
---
You are building an architecture for one of your clients with a requirement of streaming millions of requests with high availability and durability along with HIPAA compliance. Which managed service will you prefer? 
- Cloud Dataproc
---
Your software team is developing a distributed application and wants to send messages from one application to another. Once the consuming application reads a message, it should be deleted. You want your system to be robust to failure, so messages should be available for at least three days before they are discarded. Which GCP service is best designed to support this use case?
- [x] Cloud Pub/Sub
---
Your team has deployed a GKE cluster having 3 nodes for high availability. The cluster was tested multiple times before moving to production, but it suddenly stopped working after deploying it to the production environment. A team member approached you that he will need shell access to the container for a while to resolve the issue. Which command will give him access to the container?
- kubectl ssh web-server /bin/bash
---
There are 15 VMs in your company’s Google Cloud account which have public IP addresses but are ephemeral. Your manager asked you to assign static public IP to each instance. During the process, you were able to assign IPs to only 5 of the VMs and were receiving errors in all other instances. What can be the reason?
- [x] Your quota has been exhausted and you can raise a request to increase it.
---
Your team has deployed a few windows web servers on a custom VPC network and the same is running properly. After a few hours of the app suddenly crashes, developers are trying to remote access web servers, but are failing to do so. While troubleshooting the issue you realize that the firewall rule is missing. Which command will help you solve the problem?
- gcloud compute firewall-rules create “remote-access” --network “my-network” --allow tcp:22
---
A development team works with two Cloud Functions using node.js code. Each function corresponds to environments for development and production. The code is the same except for the Cloud SQL database values used in each function. The team wants to maintain code in a clean and reusable fashion and decides to pass the database value during function execution. Which feature will allow you to do this?
- [x] Environment Variables
---
Your company was bidding on a big data project for the last few months and they have finally received the project. The project wants you to deploy Apache Spark clusters on Google Cloud. Which service will you use?
- Cloud Composer
---
You as a Senior Cloud Engineer doing proofs-of-concept (POC) on a business-critical application having a database deployed on a GCE virtual machine. The requirement is to have a disk that supports up to 35,000 Read IOPS per instance. Which of the following disks is suitable to meet the requirement?
- Local SSD (NVMe)
---
You are launching VMs for your company’s internal application via CLI and you are not able to recollect one of the flags. Using which command you can help yourself?
- gcloud compute help instances create
---
You want to rename an object stored in a bucket. What command structure would you use?
- [x] gsutil mv gs://[BUCKET_NAME]/[OLD_OBJECT_NAME] gs://[BUCKET_NAME]/[NEW_OBJECT_NAME]
---
A web application is hosted on VM and its resources are stored in a bucket. You have been asked to let any authenticated user access the very high level blueprint of the company's product. This blueprint does not contain any confidential data or IP data so can be made available to the public as well. What changes are required to make it work?
- Create a new entry in permission with allAuthorizedUsers having public permission.
---
A health care company that provides medical services to the users wants to track their network forensics, real-time security analysis, and optimize the expense. The manager would like to track the network sent from and received by VM instances. What do you suggest they do?
- Cloud Storage
---
A GKE cluster was created with 4 nodes initially and after looking at the few months of monitoring report you realized that cluster is underutilized. You plan to reduce the number of nodes to 3 to save the cost. Which gcloud command will help you do that?
- [x] gcloud container clusters resize work-cluster --num-nodes=3  
---
You are trying to get Google Kubernetes server configuration of a project by running the command gcloud container get-server-config, when you hit enter, you get an error message: “There was a problem refreshing your current auth tokens: invalid_grant: Bad Request”. What would you do to successfully run this command and get the server configuration from Kubernetes?
- gcloud components update
---
Suggest the maximum number of containers you can launch within a GKE cluster:
- Unlimited
---
You want to list roles assigned to users in a project called ace-exam-project. What gcloud command would you use?
- [x] gcloud projects get-iam-policy ace-exam-project
---
Using the principle of least privilege, your colleague Bob needs to be able to create new instances on Compute Engine in the project ‘Project A’. How should you give him access without giving more permissions than is necessary?
- [x] Give Bob Compute Engine Instance Admin Role for Project A.
---
You are creating a firewall rule for your DB server so that only web servers and your internal application servers can access it. You have added both service accounts and tags for traffic filters but while saving you receive an error. What can be the reason?
- You can only specify only one traffic filter at a time.
---
An auditor needs to review audit logs. You assign read-only permission to a custom role you create for auditors. What security best practices are you following?
- Separation of duties
---
Your company hired a Big Data consultant for creating real-time reporting applications using Google Cloud services like BigQuery and PowerBI reporting tool. Your manager asked you to create an IAM user which gives him access to read, update, and delete the dataset but not to create one. Which role would you assign to him?
- roles/bigquery.datasetEditor
---
Your company has deployed an application using Google App Engine flexible environment and you have been asked to ssh the VM instance in a flexible environment, update the app configuration and if required, enable and disable the App Engine application, which of the following predefined roles has access to perform these tasks?
- App Engine Service Admin
---
Your company has uploaded some business-critical documents to Cloud Storage and your project manager wants you to restrict access to the objects by using ACLs. Which of the following permission would allow you to update the object ACLs?
- [x] storage.objects.setIamPolicy
---
When you navigate to IAM & Admin in Cloud Console, what appears in the main body of the page?
- Roles and permissions assigned
---
You have been asked to create VPC for a two-tier architecture for the frontend and backend of the application. Additionally, you need to make sure that backend instances are only reachable via frontend instances. What is the best approach to achieve this?
- Add network tags to your frontend instances and use them under the targets section while creating a firewall for the backend instance.
---
Your company is going for an audit and the auditor has approached you to provide them with all the audit logs related to the bangkit-prod project. Which service will you use to extract the logs for auditors?
- Stackdriver logging
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

-
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

- 
---

-
---

-
---

-
---

- 
---

-
