# Security Lab: Monitor an EC2 Instance 

## Objective 
Create an Amazon SNS notification, congifure a cloudwatch alarm, stress test an EC2 instance, confirm that an Amazon SNS email was sent and create cloudwatch dashboard

## Tasks 
- Conifgure Amazon SNS - I created a SNS topic to send alerts and subscribed my email to it. This way if something happens in AWS, the system can send me a message automatically. 
- Create cloudwatch alarm - I made a CloudWatch alarm to watch the CPU usage of the EC2 instance. If the CPU went above 60%, the alarm would trigger and send an email through the SNS topic.
- Test the cloudwatch alarm - I ran a stress on the EC2 to make the CPU go over 60%. I saw the alarm change to "In Alarm" in CLoudWatch and got the email alert. This showed that what I did worked.
- Create a cloudwatch dashboard - I created a dashboard in CloudWatch to see the CPU usage of the EC2 instance in real time. This makes it easy to monitor the instance without checking manually. 

## Challenges 
One challenge was that the CPU took time to go over 60%, so I could not receive the email notification during the test. 

## Takeaways 
I learned how to set up Amazon SNS for notifications, create and test Cloudwatch alarms, and build a CloudWatch dashboard to monitor EC2 metrics. 

## Screenshots
<img width="1470" height="831" alt="Screenshot 2025-08-10 at 18 38 59" src="https://github.com/user-attachments/assets/b8e49d6a-8094-44be-a504-c5953af14b02" />
<img width="1470" height="832" alt="Screenshot 2025-08-10 at 18 40 03" src="https://github.com/user-attachments/assets/1f95bd7b-5189-441d-8e0d-688ccf803413" />
<img width="1470" height="831" alt="Screenshot 2025-08-10 at 18 50 12" src="https://github.com/user-attachments/assets/a5151425-9231-4e2a-9f31-6e24046b3a68" />
<img width="1470" height="831" alt="Screenshot 2025-08-10 at 18 50 40" src="https://github.com/user-attachments/assets/bbc5a129-835f-4557-bc7c-a22800b4b964" />
<img width="1470" height="831" alt="Screenshot 2025-08-10 at 19 04 41" src="https://github.com/user-attachments/assets/d3aaf48f-4496-46d6-aa2b-58462b4a09a8" />
<img width="1470" height="831" alt="Screenshot 2025-08-10 at 19 09 50" src="https://github.com/user-attachments/assets/a5a6ca8f-479b-4817-9e4f-4725ee1d1c5f" />
<img width="1470" height="828" alt="Screenshot 2025-08-10 at 19 19 33" src="https://github.com/user-attachments/assets/76f946fe-4726-4c91-b34b-47d845fd17d1" />
<img width="1470" height="835" alt="Screenshot 2025-08-10 at 19 19 56" src="https://github.com/user-attachments/assets/1ba47017-2b17-4f76-bb21-8c4e3458b953" />
<img width="1470" height="830" alt="Screenshot 2025-08-10 at 19 27 49" src="https://github.com/user-attachments/assets/451090f0-4f88-48df-bb2a-a4b3771aca43" />
<img width="1465" height="829" alt="Screenshot 2025-08-10 at 19 31 56" src="https://github.com/user-attachments/assets/033f12bf-f5eb-4976-95de-dba29e3ea89a" />
