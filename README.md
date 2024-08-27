# ScalableEmployeeManager

**ScalableEmployeeManager** is a project designed to store and manage employee data efficiently, ensuring robust performance under varying loads. This system leverages Amazon Web Services (AWS) for scalable and reliable infrastructure, incorporating RDS for data storage and EC2 for backend processing. 

## Project Overview

The project involves the following components:
- **Amazon RDS**: Used for storing employee data such as names and emails.
- **Amazon EC2**: Hosts the backend PHP application.
- **Load Balancer**: Distributes incoming traffic across multiple EC2 instances to ensure high availability and reliability.
- **Auto Scaling Group**: Automatically adjusts the number of EC2 instances based on traffic demands.
- **DNS**: Provides a stable and user-friendly URL to access the website.

## Benefits

- **Scalability**: With an auto-scaling group, the system can handle varying levels of traffic efficiently by adjusting the number of EC2 instances.
- **High Availability**: The load balancer ensures even distribution of traffic, minimizing the risk of server overload and downtime.
- **Accessibility**: DNS allows users to access the website through a consistent domain name.
- **Security**: The setup allows secure communication between EC2 and RDS instances, protecting sensitive data.

## Usage

1. **Access the Website**: Use the DNS-provided URL to access the website where you can manage employee data.
2. **Data Storage**: Employee information such as names and emails is stored securely in the RDS instance.
3. **Load Handling**: The auto-scaling feature ensures that the website remains responsive even under high traffic conditions.
4. **Traffic Management**: The load balancer efficiently distributes incoming requests to different EC2 instances.

## Getting Started

1. **Setup AWS Services**:
   - Create an RDS instance for database management.
   - Launch an EC2 instance and deploy the PHP application.
   - Configure the auto-scaling group and load balancer.

2. **Configure DNS**:
   - Set up a DNS record to point to the load balancer’s endpoint.

3. **Deploy Application**:
   - Upload the PHP files to the EC2 instance.
   - Ensure the PHP application is properly configured to connect to the RDS instance.

4. **Test**:
   - Verify that the website is accessible via the DNS URL.
   - Test the functionality of data storage and retrieval.



## Contact

For any questions or feedback, please contact akankshachaudhari321@gmail.com

---

Thank you!
