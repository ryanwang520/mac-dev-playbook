# Mac Development Ansible Playbook

This playbook installs and configures most of the software I use on my Mac for web and software development. Some things in macOS are slightly difficult to automate, so I still have a few manual installation steps, but at least it's all documented here.

## Installation

  1. Run `ansible-galaxy install -r requirements.yml` inside this directory to install required Ansible roles.
  1. Run `ansible-playbook main.yml` inside this directory.
