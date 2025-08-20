# My Parrot-Build
This repo customizes Parrot OS setup with Ansible.


## Prerequisites
Make sure you install the Ansible requirements before running the playbook


## Usage
```bash
git clone https://github.com/<your-user>/parrot-build.git
cd parrot-build
ansible-galaxy install -r requirements.yml --force
ansible-playbook main.yml -K

```
