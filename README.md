Role Qemu-guest-agent
=========

Install and enable qemu-guest-agent

Requirements
------------

ansible 3.1.2+\
ansible-galaxy 2.16.11+\
Not tested on earlier versions

Role Variables
--------------

None.

Dependencies
------------

user in sudoers 

Example Playbook
----------------

```
- name: Install and enable qemu-auest-agent
  hosts: host
  become: yes
  roles:
    - Qemu-guest-agent
```

License
-------

BSD-3-Clause

Author Information
------------------

Murzabaev Marat (murzik2142@gmail.com)