# lynis-playbook
This ansible playbook helps to perform lynis audit on multiple machines at once.


## Table of Contents
- [Installation](#installation)
- [Usage](#usage)


## Installation
1. Ensure Ansible is installed on your machine
2. Clone this git repository


## Usage
1. Switch current directory to the cloned repo
2. Replace example domains with your server's domain/IP, replace username and path to your SSH key in the [inventory](./inventory) file
3. To run the playbook, execute next ansible command in your shell:
```bash
ansible-playbook main.yml
```

