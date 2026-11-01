AWS Network Architecture
Region
London (eu-west-2)
Network Design
VPC: Secure-Cloud-VPC
CIDR: 10.0.0.0/16
Public Subnet: Public-Subnet-1
Subnet CIDR: 10.0.1.0/24
Internet Gateway: Secure-Cloud-IGW
Route Table: Public-Route-Table
Security Group: Secure-Web-SG
Traffic Flow
Internet → Internet Gateway → Route Table → Public Subnet
Security
HTTP access on port 80
Inbound source restricted to My IP
Outbound rules reviewed
