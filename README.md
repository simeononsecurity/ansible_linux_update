# Ansible Role: linux_update

[![Sponsor](https://img.shields.io/badge/Sponsor-Click%20Here-ff69b4)](https://github.com/sponsors/simeononsecurity) 

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
For more information, visit [SimeonOnSecurity.com](https://simeononsecurity.com).

## [Learn more about Automating Linux Patching with Ansible](https://simeononsecurity.com/guides/automate-linux-patching-and-updates-with-ansible/)
<a href="https://simeononsecurity.com" target="_blank" rel="noopener noreferrer">
  <h2>Explore the World of Cybersecurity</h2>
</a>
<a href="https://simeononsecurity.com" target="_blank" rel="noopener noreferrer">
  <img src="https://simeononsecurity.com/img/banner.png" alt="SimeonOnSecurity Logo" width="300" height="300">
</a>

### Links:
- #### [github.com/simeononsecurity](https://github.com/simeononsecurity)
- #### [simeononsecurity.com](https://simeononsecurity.com)

