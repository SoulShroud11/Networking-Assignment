Introduction: 

The objective of this repoistory is to offer insight and function as a SOP - Standard Operating Procedure with respect to a specific task. The task at hand is to deploy docker containers onto a managed node with the ability to run services like an Apache web server and FTP (File Transfer Protocol) The deployment should take place via Ansible.
  
Ansible is an open source IT automation engine that automates provisioning, configuration management, application deployment, orchestration, and many other IT processes. - “Redhat.com, Learning ansible basics write up.”

This report is to be utilized for educational purposes only. The owner of this document is simply writing this report with respect to a research project/assignment conducted at Dublin Business School for their Masters in Cyber Security course, January 2024. Changes to this document may be necessary in near future as per the updates and versions of the pre requisites used in this assignment.

Pre-Required Components:

1. Ansible Playbook Reference - https://github.com/SoulShroud11/Networking-Assignment/blob/main/playbook.yml

2. Python3-pip on Managed Node - https://linuxize.com/post/how-to-install-pip-on-ubuntu-22.04/
   
3. Ansible installed on Master Node - https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-ansible-on-ubuntu-22-04
   
4. Docker installed on Managed Node - https://docs.docker.com/engine/install/ubuntu/

5. OpenSSH on master and managed Node -
https://hostman.com/tutorials/how-to-install-and-configure-ssh-on-ubuntu-22-04/

Summary: The deployment of Docker containers for the Apache web server and FTP services on a Managed Node, a virtual machine running Ubuntu 22.04 LTS (Jammy) is used in this assignment for demonstration. Ansible playbook (playbook.yml) running from a Master computer which is also an Ubuntu 22.04 LTS helps in the deployment process.



