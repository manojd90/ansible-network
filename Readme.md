# Cisco IOS/XE Configuration Playbook

This Ansible playbook configures Cisco IOS/XE devices with the following tasks:

- Add a login banner
- Create a Loopback interface
- Assign multiple IP addresses to the Loopback interface
- Add static routes
- Verify configuration by printing interface and route details

---

## Prerequisites

- Ansible 2.10+ installed
- `cisco.ios` Ansible collection installed:

```bash
ansible-galaxy collection install cisco.ios


## References and Documentation

- Ansible Cisco IOS Collection Overview - https://docs.ansible.com/ansible/latest/collections/cisco/ios/index.html  
- Ansible ios_facts Module - https://docs.ansible.com/ansible/latest/collections/cisco/ios/ios_facts_module.html  
- Ansible ios_interfaces Module - https://docs.ansible.com/ansible/latest/collections/cisco/ios/ios_interfaces_module.html  
- Ansible ios_l3_interfaces Module - https://docs.ansible.com/ansible/latest/collections/cisco/ios/ios_l3_interfaces_module.html
- Ansible ios_command Module] - https://docs.ansible.com/ansible/latest/collections/cisco/ios/ios_command_module.html

