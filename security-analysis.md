AWS Secure Cloud Network – Security Analysis
1. Security Objectives
The main objective of this project is to build a basic AWS network with controlled internet access and restricted inbound traffic.
2. Network Security
Created a dedicated Virtual Private Cloud (VPC).
Configured a public subnet.
Connected the VPC to an Internet Gateway.
Configured route tables to control network traffic.
3. Security Group Analysis
Configured HTTP access using TCP port 80.
Restricted inbound traffic to a specific source IP.
Reviewed outbound traffic rules.
4. Potential Security Risks
Public-facing resources may be exposed to internet-based attacks.
Unrestricted outbound traffic may increase security risks.
HTTP traffic is not encrypted.
5. Security Recommendations
Use HTTPS (port 443) instead of HTTP whenever possible.
Allow only necessary inbound traffic.
Restrict outbound traffic based on application requirements.
Monitor network activity and review security rules regularly.
Avoid exposing administrative ports such as SSH and RDP to the public internet.
6. Project Limitations
This project demonstrates basic AWS network configuration. EC2 connectivity testing, HTTPS configuration, and advanced monitoring have not yet been implemented.
7. Conclusion
This project provided practical experience with AWS networking concepts and basic cloud security configurations.
