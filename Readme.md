---
What is the gcloud command to set default zone for compute engine server using gcloud CLI?
- [x] gcloud config set compute/zone us-east1-a
---
You created a bucket in cloud storage and uploaded some files and then enabled object versioning on it. Which version the files you have already added will have?
- x
---
You have been hired as a contractor by one of the travel technology companies that is planning to containerize their existing applications in such a way that they can perform a lift and shift very easily in the future if they plan to move away from Google Cloud. Which service will best suit this case?
- [x] Kubernetes Engine
---
Being a Senior Cloud Engineer of the company, you are asked to launch a managed MySQL DB using custom VPC with network range of 172.17.0.0/16 on Google Cloud keeping security at utmost priority allowing team members to access it only over a private channel. You completed the setup with all the requirements, but developers are unable to access DB over the private network via application hosted on VM. What can be the reason?
- [x] You did not whitelist 172.17.0.0/16 in the firewall.
---
Which command will let you enable Google Compute service using gcloud CLI?
- gcloud service compute enable
---
You are working for a genomics company in the US that is planning to conduct data analysis on around 10 TB of data. The company would require 20 vCPUs and 60GB of RAM for the same. You have been asked to figure out the cheapest option to conduct the analysis. Which of the following would you use?
- Cloud Functions
---
Your program manager wants you to set up a hybrid network between your Google Cloud and on-premise infrastructure that allows high bandwidth, low latency connection between both the networks. As a Sr. Cloud Engineer, which one of the following services will you select?
- Shared VPC
---
Engineering team is building an application which routes requests on the TCP layer. They need a load balancer with support of SSL termination on load balancer. Which of the following is the best available option?
- HTTPS Load Balancer
---
Your team is building a media collection and analysis application for one of your clients. They have asked you to enable Google Photos API and YouTube API. Moreover, they want to test the API without integrating it within the application. Which service would help your development team test the API without integration?
- API Library
---
You are working for a service company that has an automobile client. The client has developed an application for internal use with Erlang and has approached your company to help him to ease the application deployment process on Google Cloud. The company does not have highly trained people, so it wants you to deploy the application in such a way that post-deployment, they will be able to manage it without worrying about the infrastructure. Which of the following services would you prefer?
- [x] App Engine Flexible
---
You are planning to build a microservice application with docker containers and want to host them on Google Cloud as stateless and serverless. Which service will help you serve the need?
- App Engine Flexible
---
Your engineering team has developed an application which will be deployed using GKE. The application needs a monitoring agent running on each node without fail and any change in the number of nodes should also update the count of the monitoring agent. Which API resource would you use to achieve the desired result?
- StatefulSet
---
You were inspecting the containers on a VM and found out that a pod is running which is no more required. You try to delete it but every time a new pod is created. What do you need to delete now for removing that pod?
- [x] ReplicaSet
---
You have a website hosted on a Compute Engine VM. Users can access the website using the domain name you provided. You do some maintenance work on the VM and stop the server and restart it. Now users cannot access the website. No other changes have occurred on the subnet. What might be the cause of the problem?
- You do not have enough addresses available on your subnet.
---
A team of developers has been working on a Java 8 application on their local machine but the company has now decided to create Windows VM for the team and let them work on VM instead of working on a local machine. Additionally, your manager has asked to send all stack traces to a common place. Which service would you use to meet the following requirement?
- Stackdriver Logging
---
You have an application running on Google Cloud VM written in C#.Net for the last few weeks. Suddenly you experience elevated latency and poor performance among application endpoints. Which service can help you troubleshoot this issue?
- Stackdriver Monitoring
---
Your client wants to migrate their 30 TB of Hadoop or Spark cluster from an RHEL 6.5 on-premise server to Google Cloud Platform. Which of the following services can be used at the GCP end?
- App Engine
---
You are working as a system administrator and have been asked to make sure that all images are patched up to date and developers are not allowed to use old images that are not up to date as per PCI compliance. How would you achieve this?
- Mark image as deprecated to prevent users from using the old image.
---
You deployed 10 microservices using Google Kubernetes Engine. The command kubectl run deployed the microservices in different pods, 2 weeks later your manager asked you to delete the pods as the services were no longer needed. Which of the following options is the best way to delete the pods?
- gcloud container clusters delete pod
---
Your company has purchased a threat detection service from a third party and has asked you to upload all network logs to the application. Which of the following service will meet your requirements?
- Activity Logs
---
A new junior engineer is joining your team. Your manager asks you to create an IAM user for him. You are trying to create an IAM user for the new joiner, but you receive an error saying: “Email addresses and domains must be associated with an active Google Account or Google Apps Account”. What is the possible reason for this?
- You need to ask the new joiner to attach permission to his GSuite account to allow you to create an IAM user.
---
Which is the correct command to bind an IAM policy to a service account at an organization or folder level?
- [x] gcloud organizations add-iam-policy-binding org_id --member serviceAccount:dicoding@dicoding-prj.iam.gserviceaccount.com --role roles/viewer
----
PT Bangkit has deployed an application using Google App Engine standard environment. You have been asked to update the cron schedules and default cookie expiration time, which of the following predefined roles has access to update default cookie expiration but no access to update cron schedules?
- Storage Caching
---
Your client wants you to update a viewer role in your google cloud platform project using CLI. The roles have access to the App Engine list and get method and you have been asked to add the cloud storage list and get permissions. The changes were reflected after you ran the command but the user complained that they are unable to view the content of Cloud Storage buckets using CLI. What could be the most appropriate reason?
- Cloud Storage permission needs to be created and attached separately.
---
You want to list permissions in a role using Cloud Console. Where would you go to see that?
- IAM & Admin; select Roles. All permissions will be displayed.



-
---

