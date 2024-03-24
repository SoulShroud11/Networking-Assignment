Introduction: 

The objective of this repoistory is to offer insight and function as a SOP - Standard Operating Procedure with respect to a specific task. The task at hand is to deploy docker containers onto a managed node with the ability to run services like an Apache web server and FTP (File Transfer Protocol) The deployment should take place via Ansible.
  
Ansible is an open source IT automation engine that automates provisioning, configuration management, application deployment, orchestration, and many other IT processes. - “Redhat.com, Learning ansible basics write up.”

This report is to be utilized for educational purposes only. The owner of this document is simply writing this report with respect to a research project/assignment conducted at Dublin Business School for their Masters in Cyber Security course, January 2024. Changes to this document may be necessary in near future as per the updates and versions of the pre requisites used in this assignment.

Pre-Required Components:

1. Github Repository - https://github.com/SoulShroud11/Networking-Assignment/tree/main
   
2. Ansible installed on Master Node - https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-22-04
   
3. Docker installed on Managed Node - https://docs.docker.com/engine/install/ubuntu/

Summary: The deployment of Docker containers for the Apache web server and FTP services on a Managed Node, a virtual machine running Ubuntu 22.04 LTS (Jammy) is used in this assignment for demonstration. Ansible playbook (playbook.yml) running from a Master computer which is also an Ubuntu 22.04 LTS helps in the deployment process.
  
Objective: Deploying FTP and Apache web servers inside docker containers is the main objective of the task given, which will guarantee efficiency and consistency throughout deployments and can be done on multiple managed nodes. For this assignment, we are utilizing only 1 managed node.

Infrastructure: The Docker containers are hosted by the Managed Node. The virtual machine is set up with Docker runtime environments enabled. The Master computer serves as the control/master node for managing Ansible deployments.

Docker Container Deployment: The creation and configuration of Docker containers for the Apache web server and FTP services via an Ansible playbook are covered in detail in the study. To encapsulate and compartmentalize dependencies and simplify deployment across several environments, every service is containerized.

Ansible Playbook: Automating deployments is accomplished by running an Ansible playbook from the Master machine. The playbook outlines the steps needed to set up network ports, launch services on the Managed Node, and initialize Docker containers. It is the most crucial artifact within this assignment/task given.

Port Configuration: The ports 80 and 21 fall within the top 1023 dedicated ports  for the Apache web server and FTP services, respectively. This guarantees uniformity, common knowledge and facilitates effective traffic control in the Docker environment.

Benefits: The deployment process is made predictable, scalable, and less error-prone by utilizing Docker containers and Ansible automation. It improves flexibility and makes it easier to quickly offer services across a range of infrastructure environments and manage highly scalable, highly redundant deployment activities across multiple managed nodes.

