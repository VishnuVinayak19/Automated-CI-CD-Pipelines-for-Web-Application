# Automated-CI-CD-Pipelines-for-Web-Application
"Automated CI/CD pipelines for web applications, leveraging tools like Git, Jenkins, Docker, Kubernetes, and AWS to streamline development, testing, and deployment processes, ensuring faster time-to-market, improved quality, and reduced manual errors."
<img width="1096" height="768" alt="68747470733a2f2f6c756369642e6170702f7075626c69635365676d656e74732f766965772f30633138336264362d373366342d343534372d393365312d3532343664623565383633632f696d6167652e706e67" src="https://github.com/user-attachments/assets/380e95d5-c5da-4e98-8bd0-815162185c66" />

# Project ToolBox:-

Git Git will be used to manage our application source code.
Github Github is a free and open source distributed VCS designed to handle everything from small to very large projects with speed and efficiency
Jenkins Jenkins is an open source automation CI tool which enables developers around the world to reliably build, test, and deploy their software
Maven Maven will be used for the application packaging and building including running unit test cases
Checkstyle Checkstyle is a static code analysis tool used in software development for checking if Java source code is compliant with specified coding rules and practices.
SonarQube SonarQube Catches bugs and vulnerabilities in your app, with thousands of automated Static Code Analysis rules.
Nexus Nexus Manage Binaries and build artifacts across your software supply chain
Ansible Ansible will be used for the application deployment to both lower environments and production
EC2 EC2 allows users to rent virtual computers (EC2) to run their own workloads and applications.
Slack Slack is a communication platform designed for collaboration which can be leveraged to build and develop a very robust DevOps culture. Will be used for Continuous feedback loop.
Prometheus Prometheus is a free software application used for event/metric monitoring and alerting for both application and infrastructure.
Grafana Grafana is a multi-platform open source analytics and interactive visualization web application. It provides charts, graphs, and alerts for the web when connected to supported data sources.
Splunk Splunk is an innovative technology which searches and indexes application/system log files and helps organizations derive insights from the data.

# Jenkins Complete CI/CD Pipeline Project Runbook

Create a GitHub Repository with the name Jenkins-Realworld-CICD-Project and push the code in this branch(main) to your remote repository (your newly created repository).

Go to GitHub: https://github.com
Login to Your GitHub Account
Create a Repository called Jenkins-Realworld-CICD-Project
Clone the Repository in the Repository directory/folder on your local machine
Download the code in in this repository "Main branch": https://github.com/awanmbandi/realworld-cicd-pipeline-project.git
Unzip the code/zipped file
Copy and Paste everything from the zipped file into the repository you cloned in your local
Open your Terminal
Add the code to git, commit and push it to your upstream branch "main or master"
Add the changes: git add -A
Commit changes: git commit -m "adding project source code"
Push to GitHub: git push

# Create An IAM Profile/Role For The Ansible Automation Engine (Dynamic Inventory)

Create an EC2 Service Role in IAM with AmazonEC2FullAccess Privilege
Navigate to IAM

* Click on Roles
* Click on Create Role
* Select Service Role
* Use Case: Select EC2
* Click on Next
* Attach Policy: AmazonEC2FullAccess
* Click Next
* Role Name: AWS-EC2FullAccess-Role
* Click Create

# Jenkins/Maven/Ansible

Create a Jenkins VM instance
Name: Jenkins/Maven/Ansible
AMI: Ubuntu 24.04
Instance type: t2.medium
Key pair: Select or create a new keypair
Security Group (Edit/Open): 8080, 9100 and 22 to 0.0.0.0/0
IAM instance profile: Select the AWS-EC2FullAccess-Role
User data 
Launch Instance
<img width="1710" height="755" alt="sagdsgfsa" src="https://github.com/user-attachments/assets/38b6c76d-d61f-4fff-b76c-5240552b5d96" />
<img width="1698" height="519" alt="fwefwrfwrsgvsd" src="https://github.com/user-attachments/assets/b189310d-564b-45cd-a412-ea6c0c9e05cd" />

# Refresh your Grafana Dashbaord


<img width="1400" height="659" alt="1_KimwgjULRZzONpjGFH1sTA (1)" src="https://github.com/user-attachments/assets/582c1109-fc8e-4f80-94c1-130e752f8874" />



