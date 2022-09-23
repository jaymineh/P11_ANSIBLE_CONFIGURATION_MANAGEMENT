# Project 11 - Ansible Configuration Management

In this project, I implemented a solution using Jenkins & Ansible. Here, when code changes have been reviewed and pushed to the main branch, Jenkins runs a job and the new changes are dumped to the Jenkins server (which is acting as a bastion host). From there, the Ansible script is run against the respective machines. SSH agent is also configured here to allow ansible connect to the remote servers.

![image](https://user-images.githubusercontent.com/91850543/191934261-ab805bdf-ccfd-4a85-94b5-b0f46920d906.png)

Kindly check `project.md` for more information.
