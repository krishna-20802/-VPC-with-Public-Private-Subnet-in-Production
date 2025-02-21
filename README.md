# -VPC-with-Public-Private-Subnet-in-Production
VPC with Public-Private Subnet in Production
This is the most recommend approach by aws if you want deploy to your application securely in a EC2 instance.
This example demonstrates how to create a VPC that you can use for servers in a production environment. To improve resiliency, you deploy the servers in two Availability Zones, by using an Auto Scaling group and an Application Load Balancer. For additional security, you deploy the servers in private subnets. The servers receive requests through the load balancer. The servers can connect to the internet by using a NAT gateway. To improve resiliency, you deploy the NAT gateway in both Availability Zones.
The following diagram provides an overview of the resources included in this example. The VPC has public subnets and private subnets in two Availability Zones. Each public subnet contains a NAT gateway and a load balancer. The servers run in the private subnets, are launched and terminated by using an Auto Scaling group, and receive traffic from the load balancer. The servers can connect to the internet by using the NAT gateway.
![image](https://github.com/user-attachments/assets/0a1ba03d-cfc5-4cff-a67c-57daee7f5e5c)

