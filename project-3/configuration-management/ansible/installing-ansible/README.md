
# Installing Ansible

## Prerequisites

For your control node (the machine that runs Ansible), you can use nearly any UNIX-like machine with **Python 3.8** or newer installed. This includes Red Hat, Debian, Ubuntu, macOS, BSDs, and Windows under a Windows Subsystem for Linux (WSL) distribution

Also, Ansible uses Secure Shell Protocol **SSH** to connect to hosts, so a dependency on **OpenSSH Client** must be met as well

## Installing on a local development environment

Following the instructions for creating a [local development environment](../../../local-dev-environment)

Check the latest version of Ansible from the project page on [Python Package Index](https://pypi.org/project/ansible/)

```sh
pip install ansible
```

Verify installation

```
ansible --version
ansible-playbook --version
```
