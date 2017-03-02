[![License](https://img.shields.io/badge/license-Apache%202-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)

Devstack Role
===================

Install [DevStack](https://docs.openstack.org/developer/devstack/)

Role Variables
--------------
```
devstack_user: "devstack"
devstack_user_home: "/home/{{devstack_user}}"
devstack_git_branch: "master"
```

Example Playbook
----------------
```
- hosts: server
  roles:
  - { role: 'grycap.devstack'}
```

Contributing to the role
========================
In order to keep the code clean, pushing changes to the master branch has been disabled. If you want to contribute, you have to create a branch, upload your changes and then create a pull request.  
Thanks
