# AWS DevOps Engineer Intern Assignment

## Objective
Deploy a simple HTML website on an AWS EC2 Ubuntu instance using Nginx.

## Task 1: AWS EC2 Setup
- Launched an Ubuntu EC2 instance.
- Created a Security Group.
- Allowed inbound SSH (22) and HTTP (80).
- Connected to the instance using PuTTY.

## Task 2: Linux Basics
Commands executed:
```bash
sudo apt update
sudo apt install nginx -y
sudo systemctl status nginx
sudo systemctl restart nginx
df -h
free -h
ps aux
```

## Task 3: Website Deployment
- Created a custom `index.html`.
- Replaced the default Nginx page.
- Verified the website using the EC2 Public IP.

## Task 4: Git & GitHub
- Created a GitHub repository.
- Uploaded `index.html` and `README.md`.

## AWS Services Used
- Amazon EC2
- Security Group
- Key Pair

## Learnings
- EC2 instance management
- SSH using PuTTY
- Linux administration
- Nginx web hosting
- GitHub repository management
