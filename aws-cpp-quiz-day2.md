# AWS Cloud Practitioner Practice Questions (Day 2)

## 1. What is a Point of Presence (PoP) in AWS?

- A. A data center where EC2 instances run
- B. A location used to deliver content to end users with low latency
- C. An internal AWS billing system
- D. A backup storage location for S3

## 2. Which AWS services use Points of Presence (PoPs)?

(Choose TWO)

- A. Amazon S3
- B. AWS CloudFront
- C. Amazon RDS
- D. AWS Global Accelerator
- E. Amazon EC2

## 3. What is the primary benefit of AWS PoPs?

- A. Lower storage costs
- B. Improved internal AWS network speeds
- C. Reduced latency for global users
- D. High CPU compute capacity

## 4. How do AWS PoPs relate to AWS Regions and Availability Zones?

- A. They are the same as Availability Zones
- B. They are subsets of Regions
- C. They are global endpoints for content delivery, separate from Regions and AZs
- D. They replace the need for Regions

## 5. Which of the following is stored or cached at an AWS PoP location?

- A. EBS volumes
- B. CloudFormation templates
- C. Cached content from CloudFront
- D. EC2 snapshots

## 6. Which AWS service provides static IP addresses to route traffic globally with low latency?

- A. Amazon Route 53
- B. AWS CloudFront
- C. AWS Global Accelerator
- D. Amazon API Gateway

## 7. Which AWS service operates at the DNS level to route users based on geographic location or latency?

- A. AWS Global Accelerator
- B. AWS Lambda
- C. Amazon EC2
- D. Amazon Route 53

## 8. Which statement BEST describes the difference between Route 53 and Global Accelerator?

- A. Both provide IP-based routing with failover capabilities
- B. Route 53 uses Anycast IPs, while Global Accelerator uses DNS
- C. Route 53 uses DNS to route traffic; Global Accelerator uses IP and AWS network backbone
- D. Global Accelerator supports DNS routing based on TTL

## 9. What is a benefit of using Global Accelerator over Route 53?

- A. Dynamic hostname resolution
- B. TTL-based latency optimization
- C. Real-time health check-based failover and lower latency via AWS backbone
- D. Lower DNS propagation delay through caching

## 10. Which of the following use cases is MOST suitable for AWS Global Accelerator instead of Route 53?

- A. Routing users to different servers based on country
- B. Serving cached content via edge locations
- C. Providing fixed IPs for multiplayer game servers requiring low latency
- D. Mapping domain names to S3 static websites

## 11. What is a Point of Presence (PoP) in the context of AWS?

- A. A physical AWS Region with multiple Availability Zones
- B. A network location for content delivery and edge services
- C. A virtual server deployed in EC2
- D. A VPC subnet optimized for high throughput

## 12. Which of the following groups consists of AWS services that **utilize Points of Presence (PoPs)**?

- A. Amazon EC2, Amazon RDS, AWS Lambda
- B. Amazon CloudFront, AWS Global Accelerator, Amazon Route 53
- C. Amazon S3, Amazon DynamoDB, Amazon Route 53
- D. AWS Elastic Beanstalk, AWS CloudFormation, Amazon VPC

## 13. How do PoPs help improve user experience in AWS Global Accelerator?

- A. By hosting databases closer to users
- B. By providing compute capacity at the edge
- C. By reducing latency through optimal routing to AWS Regions
- D. By replicating EC2 instances globally

## 14. What is the primary benefit of using AWS Direct Connect?

- A. Automatically replicates data across regions
- B. Provides a dedicated network connection from your premises to AWS
- C. Increases EC2 instance storage capacity
- D. Allows serverless compute on edge locations

## 15. Which of the following best describes the type of connection AWS Direct Connect provides?

- A. Public internet-based connection
- B. VPN tunnel over the internet
- C. Dedicated private network connection
- D. Wireless connection via satellite

## 16. AWS Direct Connect **does not** use which of the following?

- A. Dedicated physical network link
- B. AWS Edge Locations (PoPs)
- C. Virtual interfaces (VIFs)
- D. AWS Regions

## 17. What is an AWS Direct Connect location?

- A. A PoP used for CloudFront caching
- B. A physical facility where AWS Direct Connect connections are available
- C. A Region where EC2 instances run
- D. A virtual location mapped to Availability Zones

## 18. To use AWS Direct Connect, what must your network do regarding the Direct Connect location?

- A. It must connect to an AWS Availability Zone
- B. It must connect to an AWS Edge Location
- C. It must establish a dedicated network connection to a Direct Connect location
- D. It must configure a Route 53 resolver

## 19. Which of the following is true about AWS Direct Connect locations?

- A. They are only available in the same Region where your AWS resources run
- B. You must colocate your infrastructure inside the AWS data center
- C. They are hosted in third-party partner facilities that provide access to AWS
- D. They are virtual gateways attached to public VPC subnets

## 20. What is the primary purpose of AWS Outposts?

- A. To provide CDN services at the network edge
- B. To run AWS infrastructure and services on-premises
- C. To provide a DNS-based routing solution
- D. To host static websites with global reach

## 📋 Answer Key

| Question | Correct Answer(s) |
| -------- | ----------------- |
| 1        | B                 |
| 2        | B, D              |
| 3        | C                 |
| 4        | C                 |
| 5        | C                 |
| 6        | C                 |
| 7        | D                 |
| 8        | C                 |
| 9        | C                 |
| 10       | C                 |
| 11       | B                 |
| 12       | B                 |
| 13       | C                 |
| 14       | B                 |
| 15       | C                 |
| 16       | B                 |
| 17       | B                 |
| 18       | C                 |
| 19       | C                 |
| 20       | B                 |
