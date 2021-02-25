# Requirements
Dist type: 
- Archlinux
- Ubuntu
- CentOS7

## Ports
- ssh ports: 32
- nginx port: 666
- ssl port: 1443

## Usage
Run playbook:
- Archlinux:  ansible-playbook --connection=local archlinux-playbook.yml
- Ubuntu:     ansible-playbook --connection=local ubuntu-playbook.yml
- CentOS7:    ansible-playbook --connection=local CentOS7-playbook.yml
