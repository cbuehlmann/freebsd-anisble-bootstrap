# freebsd-anisble-bootstrap
Bootstrapping an Ansible based FreeBSD infrastructure

## Usage

```
ansible-playbook -b --ask-pass -c paramiko --ask-become-pass --become-method=su --user [USERNAME]
```
