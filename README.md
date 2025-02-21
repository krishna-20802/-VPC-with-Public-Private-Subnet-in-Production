# -VPC-with-Public-Private-Subnet-in-Production
VPC with Public-Private Subnet in Production
this is the most recommend approach by aws if you want deploy to your application securely in a EC2 instance   
The following diagram provides an overview of the resources included in this example. The VPC has public subnets and private subnets in two Availability Zones. Each public subnet contains a NAT gateway and a load balancer. The servers run in the private subnets, are launched and terminated by using an Auto Scaling group, and receive traffic from the load balancer. The servers can connect to the internet by using the NAT gateway.
![image](https://github.com/user-attachments/assets/0a1ba03d-cfc5-4cff-a67c-57daee7f5e5c)

