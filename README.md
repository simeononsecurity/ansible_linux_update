# Ansible Role: linux_update

This role automates Linux patching using Ansible.

## Requirements

- Linux hosts
- Ansible 2.10 or later

## Role Variables

None

## Dependencies

None

## Installation
```bash
ansible-galaxy install simeononsecurity.linux_update
```

## Example Playbook

```yaml
- name: Apply Linux updates
  hosts: linux_hosts
  become: yes

  roles:
    - linux_update
```

## License: MIT

## Author Information:
This role was created by SimeonOnSecurity.
For more information, visit [SimeonOnSecurity.ch](https://simeononsecurity.ch).

## [Learn more about Automating Linux Patching with Ansible](https://simeononsecurity.ch/guides/automate-linux-patching-and-updates-with-ansible/)

