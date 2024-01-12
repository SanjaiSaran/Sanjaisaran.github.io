# Cloud security 

#### Technical Skills: AWS, GCP, Terraform, Docker, GITHUB Action, CSPM, Artifactory.

## EDUCATION
 - Master's Degree in Cyber Forensic and Information Security | University of Madras, Chennai (2019 – 2021)
 - Post Graduate Diploma in Digital & Cyber forensics and Related Law | Institute of Forensic Science, Mumbai (2018-2019)
 - Bachelor's Degree in Mathematics | Bishop Heber College, Tiruchirappalli (2015 – 2018)

## Professional Experience
**Cloud Security Ops Engineer at Scybers (_Aug 2021 to Nov 2023_)**
 - Spearheaded the design and implementation of CSPM frameworks on both AWS and GCP platforms, ensuring the continuous monitoring and assessment of security configurations.
 - Collaborated with cross-functional teams to establish CSPM best practices and fine-tuned automated policies to align with industry standards and regulatory requirements.
 - Designed and implemented Wazuh architectures tailored for AWS and GCP environments, ensuring optimal coverage for cloud-specific threats.
 - Orchestrated the deployment of Wazuh agents across cloud instances to enable centralized log collection and analysis.
 - Configured Wazuh to seamlessly integrate with AWS CloudTrail and GCP Audit Logs, enhancing visibility into cloud-specific events.
 - Developed custom parsers and rules to extract meaningful security insights from cloud platform logs.
 - Developed comprehensive documentation for Wazuh setup, configurations, and maintenance procedures.
 - Conducted training sessions for SOC and IT teams to enhance their proficiency in utilizing Wazuh for cloud security.

## PROJECT
### Automated Security Monitoring: Deploying Wazuh on Google Cloud Platform with Terraform
[Github](https://github.com/SanjaiSaran/terraform-GCP)

The "Automated Security Monitoring: Deploying Wazuh on Google Cloud Platform with Terraform" project aims to establish a robust security monitoring infrastructure leveraging Wazuh, an open-source security information and event management (SIEM) tool. This initiative involves the use of Terraform to automate the deployment of Wazuh components on Google Cloud Platform (GCP). By utilizing Terraform's infrastructure-as-code capabilities, the project ensures a consistent and scalable deployment of Wazuh across GCP resources.
![Image](/assets/img/project_1.png)
The key components include the creation of a dedicated Virtual Private Cloud (VPC) to isolate the Wazuh infrastructure, configuration of subnetworks, firewall rules, and the deployment of virtual machine instances for Wazuh manager and potentially other components such as agents and log collectors. The project also emphasizes the automation of initial setup and configuration through custom scripts, streamlining the deployment process.

This automated security monitoring solution enhances the organization's ability to detect and respond to security threats in real-time, providing a centralized platform for log analysis, intrusion detection, and compliance monitoring. The use of GCP and Terraform ensures flexibility, scalability, and ease of management, making it an ideal solution for organizations seeking to strengthen their security posture in cloud environments.

### Dynamic IP Updater for AWS Security Groups Using Python
[Github](https://github.com/SanjaiSaran/python-aws-sg-update)

 - Objective: The project aims to automate the process of updating the allowed IP address in an AWS security group by leveraging a Python script.
![Image](/assets/img/project_2.png) 
 - Functionality: The Python script utilizes the Boto3 library to interact with AWS services, specifically targeting the EC2 security groups. It retrieves the current rules, revokes existing permissions, and authorizes the specified new IP address.
 - Security Group Management: The script enhances security group management by dynamically adapting to changes in the allowed IP address, providing a flexible and automated solution to keep security configurations up to date.
 - AWS Integration: The solution seamlessly integrates with AWS, utilizing the official AWS SDK for Python (Boto3) to interact with EC2 services, ensuring compatibility and reliability.
 - Ease of Use: By providing AWS credentials, region information, and target security group details, users can easily incorporate this script into their workflows, reducing manual intervention and enhancing the efficiency of IP address management in AWS security groups.

### Phonepe Pulse Data Visualization and Exploration
