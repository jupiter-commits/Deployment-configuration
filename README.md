In this repository you will find configurations and playbooks used to automate the continuos deployment of infrastructure

To run playbooks:
1. edit the `inventory.ini` with your own hosts
2. refactor the playbooks as you want
3. run commands like: 
``` yaml
ansible-playbook --tags ubuntu --ask-become-pass deployment.yml
```

**To Do**:
1. Complete missing plays for different machines
2. Split into roles to make it modular
3. Automate instances provisioning