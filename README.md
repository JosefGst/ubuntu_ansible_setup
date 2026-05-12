# Ubuntu Ansible Setup

My personal workstation setup using ansible.

## Prerequisites

    sudo apt install ansible
    
## Usage

    sudo ansible-pull -U https://github.com/JosefGst/ubuntu_ansible_setup.git

## Usage locally

    ansible-playbook local.yml -K

After Installation reboot the PC to make all changes take effect.

## Development

    ansible-playbook --syntax-check local.yml
    pre-commit run --all-files
    # run pre-commit whenever committing
    pre-commit install
