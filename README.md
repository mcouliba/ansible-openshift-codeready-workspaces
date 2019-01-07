Ansible Role: CodeReady Workspaces on OpenShift
=========

Ansible Role for deploying [CodeReady Workspaces](https://access.redhat.com/products/red-hat-codeready-workspaces-for-openshift/) (Eclipse Che web-based IDE) on OpenShift.

Example Playbook
------------

```
name: Example Playbook
hosts: localhost
tasks:
- import_role:
    name: mcouliba.openshift_codeready_workspaces
```

Test locally
------------
If you want to test this role locally:

```
oc login
ansible-playbook tests/test.yml
```
