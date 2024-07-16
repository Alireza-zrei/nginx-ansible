# Nginx Deployment with Ansible

This repository contains an Ansible playbook designed to automate the deployment and management of Nginx servers.

## Overview

The playbook defined in this project is intended for use in deploying and managing Nginx servers within a network. It includes tasks for updating the server packages, installing Nginx, and restarting the Nginx service upon changes.

## Prerequisites

- Ensure you have [Ansible](https://www.ansible.com/) installed on your control node.
- A target environment with Ubuntu/Debian-based systems where Nginx will be deployed.

## Getting Started

### Step 1: Clone the Repository

Clone this repository to your local machine to get started.

### Step 2: Run Ansible Playbook.yml

```
ansible-playbook -i inventory.yaml --ask-become-pass playbook.yaml
`` 


