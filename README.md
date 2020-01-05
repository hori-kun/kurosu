# Kurosu
Opinionated defaults for Crostini.

## Dependencies
A recent version of Ansible is required.

Add the following line to /etc/apt/sources.list:

```
deb http://ppa.launchpad.net/ansible/ansible/ubuntu trusty main
```

Then run these commands:

```
$ sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
$ sudo apt update
$ sudo apt install ansible
```

## Usage
Simply run the following command to configure your system with Kuroso.

```
$ ansible-playbook site.yml
```
