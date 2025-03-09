Benefits of IaC
While there are many benefits of Infrastructure as Code, a few key benefits include the simplification of cloud adoption, allowing us to quickly adopt cloud-based services and offerings to improve our capabilities. 
Infrastructure as Code allows us to remove many of the manual steps required today for infrastructure requests, giving us the ability to automate approved requests without worrying about tickets sitting in a queue. 
We can also use Infrastructure as Code to provide capacity on-demand by offering a library of services for our developers, 
even publishing a self-service capability where developers and application owners can be empowered to request and provision infrastructure that better matches their requirements. 
Again, all of this is possible while driving standardization and consistency throughout the organization, which can drive efficiencies and reduce errors or deviations from established norms.

Lab Instructions

You have been tasked with deploying some basic infrastructure on AWS to host a proof of concept environment. 
The architecture needs to include both public and private subnets and span multiple Availability Zones to test failover and disaster recovery scenarios. 
You expect to host Internet-facing applications. Additionally, you have other applications that need to access the Internet to retrieve security and operating system updates.

 1: Create a new VPC in your account in the US-East-1 region
 2: Create public and private subnets in three different Availability Zones
 3: Deploy an Internet Gateway and attach it to the VPC
 4: Provision a NAT Gateway (a single instance will do) for outbound connectivity
 5: Ensure that route tables are configured to properly route traffic based on the requirements
 6: Delete the VPC resources
 7: Prepare files and credentials for using Terraform to deploy cloud resources
 8: Set credentials for Terraform deployment
 9: Deploy the AWS infrastructure using Terraform
 10: Delete the AWS resources using Terraform to clean up our AWS environment
