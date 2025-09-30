# Automated Linux Server Configuration with Ansible

![Ansible](https://img.shields.io/badge/Ansible-2.16.3-green)
![AWS](https://img.shields.io/badge/AWS-EC2-orange)
![Ubuntu](https://img.shields.io/badge/Ubuntu-22.04-purple)

A complete Infrastructure as Code (IaC) project that automates the provisioning and configuration of a Linux web server on AWS EC2 using Ansible.

## Live Demo

- **Main Website**: http://34.236.74.89/
- **Project Page**: http://34.236.74.89/devops-project.html

## Project Overview

This project demonstrates automated server configuration management using Ansible. It transforms a bare AWS EC2 instance into a fully configured web server with:

- Automated security updates and package management
- Nginx web server installation and configuration
- Custom static website deployment
- SSH key management and security hardening

## Technologies Used

- **Ansible** (Configuration Management)
- **AWS EC2** (Cloud Infrastructure)
- **Ubuntu 22.04 LTS** (Operating System)
- **Nginx** (Web Server)

## Project Structure

## Features

### Base Role
- System updates and security patches
- Essential package installation
- Security hardening with fail2ban

### Nginx Role
- Automated Nginx installation
- Service management and configuration
- Custom homepage deployment

### App Role
- Static website deployment
- Custom HTML content management

### SSH Role
- SSH directory management
- Key-based authentication setup

## Quick Start

```bash
git clone https://github.com/PhelelaniS1/ansible-linux-configuration.git
cd ansible-linux-configuration
ansible-playbook -i inventory.ini setup.yml
