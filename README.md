# My Parrot-Build

This repo customizes Parrot OS setup with Ansible.

## Usage
```bash
git clone https://github.com/<your-user>/parrot-build.git
cd parrot-build
ansible-galaxy install -r requirements.yml
ansible-playbook main.yml -K
