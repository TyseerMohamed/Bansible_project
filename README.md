# Setup Nginx Web Server 

This Ansible playbook installs and configures an Nginx web server . It also deploys a simple HTML page.

## Prerequisites

- Ansible installed on control node
- Python 3 installed on the managed nodes


## Playbook Overview

The playbook performs the following tasks:
1. Updates the apt cache.
2. Installs Nginx.
3. Starts and enables the Nginx service.
4. Deploys a custom HTML file to the Nginx web root.
5. Ensures the Nginx service is running.


