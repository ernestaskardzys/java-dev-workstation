# Purpose

The purpose of this project is to have a Java developer's workstation which contains all the necessary software like vim, git etc.

It will install:

- Oracle JDK 11
- Docker
- Curl
- Vim
- Git

# Installation

Please edit *group_vars/all* file and add your full name, your Linux username and email. These properties will later be used in the process.

To install the packages, you need to download the contents of this repository and then perform the following:

```bash
$ sudo apt install ansible
$ ansible-playbook main.yml
```
And restart your computer - just in case.

To try that Docker works, you can try executing the following command:

```bash
$ docker run hello-world
```
