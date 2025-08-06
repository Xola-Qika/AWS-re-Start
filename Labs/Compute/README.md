# Compute Lab: EC2 Launch

## Objectives 
This lab is about launching, resizing, managing and monitoring an Amazon EC2 instance on AWS 

## Tasks
- Launching EC2 instance - I created a new EC2 instance named Web Server. I chose Amazon Linux 2 AMI and t3.micro instance type. 
- Monitor your instance - I checked CPU usage and system status in the EC2 Mointoring tab to make sure the instance was running correctly.
- Update security group and access the web server - I added an inbound rule for HTTP (port 80) from anywhere so I could acceess the web server
- Resize instance and EBS volume - I stopped the instance, changed the type to t3.small and I increased the volume from 8 GB to 10 GB 
- Test termination protection - I turned on the termination protection, tried to delete the instance and confirmed AWS blocked the action until i disabled it.

## Challenges 
- I did not face any challenges during this lab, everything was straight forward.

## Takeaways
- Make sure your security group has the correct inbound rules
- Enable the termiantion protection to avoid accidentally deleting instances 
  
## Screenshots 
<img width="1470" height="838" alt="Screenshot 2025-08-06 at 12 22 41" src="https://github.com/user-attachments/assets/648082fa-a8d4-4a66-8df9-8ebb74f220c6" />
<img width="1470" height="839" alt="Screenshot 2025-08-06 at 12 24 15" src="https://github.com/user-attachments/assets/27136b24-b433-4e43-8126-cf1ada284aa6" />
<img width="1463" height="838" alt="Screenshot 2025-08-06 at 12 33 16" src="https://github.com/user-attachments/assets/40d62115-ec6c-4cc3-be2b-b25e683ae71f" />
<img width="1470" height="836" alt="Screenshot 2025-08-06 at 12 39 17" src="https://github.com/user-attachments/assets/9bfb9216-9df9-40f3-9a70-33dce7d02cd5" /><img width="1470" height="838" alt="Screenshot 2025-08-06 at 12 40 52" src="https://github.com/user-attachments/assets/b3a344cc-8fdf-4c4d-8bca-13432b0dfdd0" />




