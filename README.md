# Ubuntu Ansible Setup

My personal workstation setup using ansible.

## Usage
    sudo ansible-pull -U https://github.com/JosefGst/ubuntu_ansible_setup.git
## Usage locally
run

    ansible-playbook local.yml -K

## Development

    ansible-playbook --syntax-check local.yml
    pre-commit run --all-files
    # run pre-commit whenever committing
    pre-commit install
