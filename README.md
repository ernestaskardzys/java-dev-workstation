# Purpose

The purpose of this project is to have a Java developer's workstation which contains all the necessary software like vim, git etc.

# Instalation

To install it, you need to download the contents of this repository and then perform the following:

```bash
$ sudo apt install ansible
$ ansible-playbook main.yml
```

Then you might want to add your current Linux username into group_vars/all file - change variable users_list - this user will be added to Docker group without using sudo. And restart your computer - just in case.

To try that Docker works, you can try executing the following command:

```bash
$ docker run hello-world
```
