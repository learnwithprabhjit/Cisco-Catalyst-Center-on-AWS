# Cisco-Catalyst-Center-on-AWS
How to Deploy Cisco Catalyst Center on AWS

Catalyst Center (Formerly Cisco DNA Center) Virtual Appliance (VA) on AWS is available for early-access customers starting now.  Now you can deploy Catalyst Center on the cloud or on-premises for enterprise and branch.  Use your existing licenses to deploy the virtual appliances on AWS and take advantage of the faster deployment, High Availability, and ability to scale out easily across all available AWS regions across the globe.  
Video explaining how to deploy with Auto mode:  http://cs.co/va-launchpad
Video explaining how to deploy with Manual mode: http://cs.co/va-manual

Form Factor
The VA form factor specs are as follows (r5a.8xlarge):  

32 vCPU 
256 GB RAM 
4 TB storage  
GP3 EBS recommended 
2500+ IOPS 
180Mbps IOPS bandwidth  
It has the scale and feature parity with DN2-HW-APL (44-core appliance) 

 

What's available
1. Auto Mode through Launchpad VA app
Cisco Virtual Appliance (VA) Launchpad helps you to create the required AWS infrastructure and completes the installation of Catalyst Center automatically. This mode makes the installation process most accessible for users who have minimal experience with AWS administration. 
Pre-requisite for Launchpad:  

AWS Account and user with Admin Privileges 
IP Address of Enterprise Firewall/Router 
Enterprise DNS IP Address 
FQDN for Cisco DNA Center 
Video explaining how to deploy with Auto mode: https://youtu.be/VVAJAInW9M4

2. Manual Mode through CloudFormation Template 
If you're familiar with AWS administration, you have the option of manually deploying the Catalyst Center AMI on your AWS account. To manually configure Catalyst Center, you need to create the AWS infrastructure, establish a connection from AWS to your enterprise, and deploy Catalyst Center VA using CloudFormation Template provided by Cisco Systems.  

Pre-requisite for Manual Mode:  

AWS Account and user with Admin Privileges 
VPC 
Subnet 
Security Group 
Connection to Enterprise Firewall/Router 
Enterprise DNS IP Address 
FQDN for Cisco DNA Center 
Video explaining how to deploy with Manual mode: https://youtu.be/HT99Tsnyj_k

 

Latency and Bandwidth Considerations
Latency requirements: Within 200ms RTT between DNAC VA on AWS and on-premises devices  

Bandwidth Requirements: Overall a 100Mbps connection will suffice for most requirements. Please be aware Netflow may use up to 4MB/s or 32Mbps at full load and Backups and SWIM transfers can use excess of 10MB/s or 80Mbps from the cloud to any on-premises servers/devices 

 

How to Access
To get access to Catalyst Center VA on AWS AMI and Launchpad App, please complete this form: http://cs.co/dnac-va-la 

For any questions, send an email to dnac-va@cisco.com  

 

Resources
Deployment is easy and can be done in less than 90 mins!  Here are resources to walk you through the deployment process: 

Deployment Guide: http://cs.co/va-guide 

Release Notes: http://cs.co/va-rn 

FAQ: http://cs.co/va-faq
