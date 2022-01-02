## Terraform-vpc-with-apache2-in-ubuntu
- Created a vpc
- Created Internet Gateway
- Created Custom Route Table
- Created a Subnet
- Associated subnet with Route Table
- Created Security Group to allow port 22,80,443
- Created a network interface with an ip in the subnet that was created in step 4
- Assigned an elastic IP to the network interfacecreated in step 7
- Created ubuntu server and install/enable apache2
