# Networking Lab: Build Your VPC and Launch a Web Server

## Objective
Create VPC, subnets, configure security groups and launch an EC2 instance into a VPC

## Tasks 
- Create your VPC -  Created a new Virtual Private Cloud with a custom IPv4 CIDR block to provide an isolated network environment.
- Create additional subnets - Created a public subnet for resources that need internet access and a private subnet for internal resources. placed them in different availability zones to improve availability.
- Associate subnets and add routes - Associated the public subnet with a route table that connects to an internet gateway, and associated the private subnet with a route table without internet access for security.
- Create a VPC security group - Created a security group allowing HTTP (port 80) from anywhere for web access 
- Launch a web server instance - Deployed an EC2 instance in the public subnet, installed a web server, and confirmed that it was accessible in a browser.

## Challenges 
I forgot to assign public IP, the EC2 intance was not accessible

Security group did not allow web traffic

## Takeaways 
Subnets must be associated with route tables. 

## Screenshots
![Uploading Screenshot 2025-08-05 at 10.33.20.png…]()

<img width="1470" height="840" alt="Screenshot 2025-08-06 at 18 26 14" src="https://github.com/user-attachments/assets/650b1635-af45-41bc-a251-b16305104849" />
<img width="1470" height="841" alt="Screenshot 2025-08-06 at 18 27 04" src="https://github.com/user-attachments/assets/f4b2b8cf-323f-4b75-94f2-29cc97eba5c0" />
<img width="1470" height="840" alt="Screenshot 2025-08-06 at 18 30 30" src="https://github.com/user-attachments/assets/7ea18751-d072-42ab-a3c3-36b900a34804" />
<img width="1470" height="840" alt="Screenshot 2025-08-06 at 18 32 39" src="https://github.com/user-attachments/assets/758911de-0379-4c43-a328-95ea1a078030" />
<img width="1470" height="840" alt="Screenshot 2025-08-06 at 18 36 40" src="https://github.com/user-attachments/assets/07e1b7fd-6f73-40a9-bdd8-24514ff4c8fa" />
<img width="1468" height="836" alt="Screenshot 2025-08-06 at 18 43 11" src="https://github.com/user-attachments/assets/e160c177-a9bf-409c-abc3-2115d52b70f1" />
<img width="1470" height="841" alt="Screenshot 2025-08-06 at 18 48 39" src="https://github.com/user-attachments/assets/f0b81c58-2daf-4e6a-81ed-43b98964301a" />
<img width="1470" height="837" alt="Screenshot 2025-08-06 at 18 49 07" src="https://github.com/user-attachments/assets/0fb82e44-9ff8-4fe7-a09e-ee8bf2947f3e" />





