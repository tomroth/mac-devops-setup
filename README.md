# DevOps Engineer MacBook Setup

This Ansible playbook automates the setup process for a DevOps Engineer's MacBook, installing necessary tools and configuring the development environment.

## Prerequisites

1. Install [Ansible](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)
2. Ensure you have Python 3 installed.

## Tools and Packages Installed

- Homebrew packages:
  - git
  - python
  - ansible-lint
- Homebrew Cask packages:
  - Visual Studio Code
  - Docker
  - iTerm2
  - 1Password
  - Slack
  - Google Chrome
- Visual Studio Code extensions:
  - hashicorp.terraform
  - github.copilot
  - ms-azuretools.vscode-docker
  - rebornix.ruby
  - wingrunr21.vscode-ruby
  - castwide.solargraph
  - streetsidesoftware.code-spell-checker

## How to Use

* Clone this repository to your local machine:

```bash
git clone https://github.com/tomroth/mac-devops-setup.git
cd mac-devops-setup
```

* Run the Ansible playbook:

```
ansible-playbook devops_setup.yml
```

* Follow any on-screen instructions, such as adding your SSH key to your GitHub account.

* Once the playbook has finished running, your MacBook will be set up with the required tools and packages for a DevOps Engineer.

## Contributing

If you'd like to add new features or make changes to this playbook, please submit a pull request with your proposed changes. Ensure your changes are well-documented and tested before submitting the pull request.

## License

This project is licensed under the MIT License.
