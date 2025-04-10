In this repository you will find configurations and playbooks used to automate the continuos deployment of infrastructure

To run playbooks:
1. edit the `inventory.ini` with your own hosts
2. refactor the playbooks as you want
3. run commands like:
``` yaml
ansible-playbook --tags ubuntu --ask-become-pass deployment.yml
```

**To Do**:
- [x] Split into roles to make it modular (See my [roles tiny script](https://github.com/jupiter-commits/Tiny-scripts/blob/36bec2a1913a5b3a07ddb8fe9f63e0f2578dac68/roles.sh) )
- [ ] Complete missing plays for different machines
- [ ] Automate instances provisioning

**Dependencies**
- Install the GitLab collection referenced form ansible galaxy `ansible-galaxy collection install srv6d.gitlab`