# DevOps Engineer MacBook Setup

This playbook sets up a new MacBook for a DevOps Engineer.

## What does it do?

The provided Ansible playbook automates the following tasks:

1. Install Homebrew packages
2. Install Homebrew Cask packages
3. Check and list installed Visual Studio Code extensions
4. Install Visual Studio Code extensions
5. Configure .zshrc file

## Usage

To use the playbook, follow these steps:

1. Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html) on your MacBook.
2. Clone this repository: `git clone https://github.com/tomroth/mac-devops-setup.git`
3. Change to the repository directory: `cd mac-devops-setup`
4. Run the playbook: `ansible-playbook mac-devops-setup.yml`

This will configure your MacBook with the specified packages and settings.
