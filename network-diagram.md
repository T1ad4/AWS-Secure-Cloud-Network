AWS Secure Cloud Network - Architecture Diagram

NETWORK TRAFFIC FLOW

INTERNET
   |
   |
Internet Gateway (IGW)
   |
   |
Public Route Table
   |
   |
Public Subnet
10.0.1.0/24
   |
   |
Security Group
HTTP - Port 80
Source: My IP
   |
   |
AWS VPC
10.0.0.0/16

NETWORK COMPONENTS

VPC: Secure-Cloud-VPC
CIDR: 10.0.0.0/16
Subnet: Public-Subnet-1
Subnet CIDR: 10.0.1.0/24
Internet Gateway: Secure-Cloud-IGW
Route Table: Public-Route-Table
Security Group: Secure-Web-SG

TRAFFIC FLOW EXPLANATION

Internet traffic reaches the VPC through the Internet Gateway.
The route table directs traffic to the public subnet.
The Security Group controls permitted inbound and outbound traffic.
