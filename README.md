# Configuration Management

Write an Ansible playbook to configure a Linux server.

## Project Overview
This project automates the configuration of a Linux server on AWS EC2 using Ansible. The playbook transforms a base Ubuntu instance into a fully operational web server with Nginx and a custom static website.

## Requirements
Configure a Linux server on **AWS EC2** with the following:

### Ansible Playbook: `setup.yml`
### Roles to create:
- **base**: System setup and security
- **nginx**: Web server installation  
- **app**: Application deployment
- **ssh**: SSH configuration

## Solution Implementation

![Ansible](https://img.shields.io/badge/Ansible-2.16.3-green)
![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-purple)

### Live Demonstration
- **Main Website**: http://34.236.74.89/
- **Project Page**: http://34.236.74.89/devops-project.html

### Technical Architecture
- **Infrastructure as Code**: Ansible
- **Cloud Platform**: AWS EC2
- **Web Server**: Nginx
- **Operating System**: Ubuntu Linux

### Project Structure
