# Ansible-Based Multi-Node Setup on AWS (Ubuntu 24.04)

This project demonstrates automating a multi-node environment on AWS using Ansible. It includes controller and node setup, user creation, SSH configuration, package installation, and connectivity verification.

## Project Duration
**Jun 2025 - Jul 2025**

## Tools & Technologies
- AWS EC2
- Ansible
- Ubuntu 24.04
- SSH
- Linux
- User Management
- Cloud Networking

## How to Use
1. Clone the repository:
```bash
git clone https://github.com/<your-username>/ansible-aws-multi-node-setup.git
2.Update inventory file with your EC2 private IPs.
3.Run playbooks in order:

ansible-playbook -i inventory playbooks/user-setup.yml
ansible-playbook -i inventory playbooks/package-install.yml
ansible-playbook -i inventory playbooks/ssh-config.yml
ansible-playbook -i inventory playbooks/verify-connectivity.yml


4.Verify connectivity by checking /tmp/testfile on Node 1 and Node 2.
Outcome

Multi-node setup automated on AWS EC2 (Ubuntu 24.04)

Passwordless sudo and SSH trust established

Remote connectivity successfully verified
