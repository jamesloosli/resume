# James Loosli

[Linkedin](https://www.linkedin.com/in/jamesloosli/) | [Github](https://github.com/jamesloosli)

## Who Am I

At heart, I am happiest when I'm building. I've been writing Infrastructure-as-Code nearly my entire career, and believe strongly in the transformative power of applying software development principles to infrastructure problems. I'm passionate about finding the solution that gets code to production in a repeatable way, while also allowing for future improvement and iteration of the solution itself. I'll learn whatever tooling I need to get a job done, but have a strong preference for Python, Gitlab, and Docker as my preferred arsenal. I find working with people to use the tools I've built to create new solutions and solve business problems to be even more rewarding than the initial individual contribution phase. I've also come to really enjoy mentoring junior engineers and peers both technically and in their career growth.

## Where I've Been
                          
**Lead Solutions Architect | Rackspace, formerly Onica | 03/2018 – Current**
  * Team lead for 6 Solution Architects and Engineers
  * Developed new framework for composing cloudformation modules with environment information into a testable, redeployable artifact using Python. Wrote documentation and presentations for other teams to be able to consume. Worked with enterprise architecture to leverage this new framework to start to build a common infrastructure platform. Business analysts projected $52 million in saved development costs per year.
  * Wrote cloudformation stacks to deploy Elasticache (specifically redis), Multiple VPC resources (subnets, security groups), IAM roles and policies, multiple lambdas. Wrote or adapted multiple custom cloudformation resources in Lambda. Used stacker post-hooks to do out-of-band configurations for things Cloudformation couldn’t cover.
  * Guided kubernetes architecture decisions for cluster scaling, dual-region failover. Created user tools for interacting with multiple EKS clusters integrated with IAM. Helped tie kubernetes RBAC to IAM roles.
  * Integrated on prem DNS with a cloud-based resolver for the applications that had been migrated. This involved using a CNAME in the customer’s zone, which pointed to a record in a zone sitting in a route53 zone. The route53 zone then could utilize AWS’s Alias A record to resolve an api gateway custom domain. Built and optimized the CD involved.
  * Helped design and build a replacement for a high volume on prem message system utilizing AmazonMQ(ActiveMQ) and SQS. Proved that the solution was not viable as a replacement for cloud services directly connecting to the on-prem messaging (TIBCO/jms) system directly.
  * Wrote a large portion of a Rest proxy for a legacy system in Java, serializing corba payloads into json. Subsequently did the deserialization work on the client side to re-assemble those objects such that the intermediary proxy didn’t require any changes to the application business logic.
                                
**Sr Devops Engineer | Auditboard, Inc | 10/2017 – 02/2018**
  * Built operations-specific replica of current infrastructure for testing in a separate AWS account. AWS components included RDS, Route53, EC2, VPC, IAM, Certificate Manager, Cloudwatch and Lambda.
  * Created additional dashboards and alerts in Sysdig to capture rates of HTTP failure responses, concurrent RDS connections.
  * Wrote a short bash script to update the firewall of an AzureDB instance. Created a daemonset definition using Helm to run that script on Kubernetes, which would dynamically allow network access to Azure for our Kubernetes nodes.
  * Updated in-house Django-based infrastructure management application to handle new resource types.
                                
**Devops Engineer | Hart, Inc | 01/2016 – 10/2017**
  * Supported legacy AWS applications running on CodePipeline, CodeDeploy, Elasticache, RDS, Elastic Beanstalk and other Amazon-specific services.
  * Audited S3 bucket permissions, tuned IAM profiles for users and applications, created new buckets as required. 
  * Initiated and led a ground-up refactor of the entire cloud-based infrastructure.
  * Built a representation of our virtual networking and security groups in Saltstack “pillars”, then built automation around that data to deploy virtual networks. This included EC2 VPC’s, Subnets, Gateways, Security Groups and Routing tables.
  * Created EC2 instance profiles for initial infrastructure, later made templates for instance profile creation.
  * Prototyped, deployed and automated deployment of Consul for service discovery, implemented a small service check library in python as a helper for registration.
  * Built a CI pipeline based around RPM packages using Jenkins and FPM. Expanded pipeline to cover Java, Go, NodeJS, and React-powered microservices and frontends.
  * Configured Github webhooks to automatically trigger Jenkins builds. 
  * Wrote a simple set of modularized Salt states which deployed each microservice, and registered them with service discovery.
  * Evangelized and participated in a weekly production release process that ensured that code releases went smoothly on a technical level and on a human level.
  * Rebuilt elasticsearch automation to run on Triton (Smart DataCenter).
  * Overhauled CI pipeline based on docker containers using docker-compose and Gitlab running on Triton.
                                 
**Linux Systems Engineer | Instant Channel | 06/2013 – 12/2015**
  * Automated entire infrastructure from manual deployment and configuration to Puppet-based, hands-free infrastructure system. Deployment flexibility allowed for a geometric increase in infrastructure resources.
  * 6 months after being hired, mail delivery staff was increased to utilize the increased available resources, and revenue increased from $200k monthly net to a peak of $500k monthly.
  * After automating the infrastructure, the role shifted to backend development and resource management.
  * Prototyped the current mainline mail delivery process, which saw peak monthly revenues of over $1 million, 12 months after being hired.
  * Negotiated lower rates for leased IP blocks by 50%. Aggressively pruned unneeded infrastructure and migrated lower-load services (LDAP, Puppetmaster, Internal webapps) to virtual machines. Saved nearly $400k per year in infrastructure and IP costs while tripling the resources available for mailing.
  * Negotiated lower domain purchase rate from $15.00/year to $9.00/year, saving $72,000 per year on domains alone.
  * Oversaw development of IP address management software after writing the server-side backend and prototyping IP over GRE tunnels.
  * Prototyped domain-management software. Responsible for the server-side code which interacted with multiple registrar APIs (enom, namecheap, godaddy).
  * Responsible for the uptime of over 10,000 individual domains, and ~16,000 IP addresses.
  * Built an end-to-end development pipeline with multiple environments, easy rollback and unit testing for Puppet, web-facing apps, internal apps, and server backend code using JenkinsCI. 
  * Built an SSH-secured APT package repository for dead-simple application installation on our debian systems for both production and testing environments.

## Where I'm Headed

Always looking for opportunities to expand both my technical and interpersonal skillsets.  

## Certifications
  * AWS Certified Developer - Associate (Validation Number HEFVTMJ1GM441HC6)
  * AWS Certified DevOps Engineer - Professional (Validation Number Z3M9WNZ1MB4E1GK5)
  * AWS Certified Solutions Architect - Associate (Validation Number WMF7S8P23NQ4Q05V)
  * AWS Certified Solutions Architect - Professional (Validation Number 9EM9SYP13FBE1LCP)
  * AWS Certified SysOps Administrator - Associate (Validation Number 7GG7TJLK3144QNC5)
  * AWS Certified Security Specialty (Validation Number YB8HKZGLJNFQ1KSR)

## Education
  * Woodbridge High School, 2004

## Volunteer and Other Experience
  * Sergeant, USMC Reserve, 2005-2013
  * Missionary, Poland Warsaw Mission, 2009-2010
  * Eagle Scout Award, 2002
