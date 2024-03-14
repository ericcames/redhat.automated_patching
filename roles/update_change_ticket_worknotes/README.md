update_change_ticket_worknotes
=========

This role will updates the change ticket work notes.

Requirements
------------
```yaml
Service Now Credential
Service Now Change ticket number
```
Role Variables
--------------
```yaml
ticket_number: 123456
```
Dependencies
------------
```yaml
servicenow.itsm
```
Example Playbook
----------------
```yaml
---
- name: Update change ticket work notes
  hosts: localhost
  connection: local

  roles:

    - name: update_change_ticket_worknotes
```
License
-------

https://spdx.org/licenses/GPL-3.0-only.html

Author Information
------------------
```yaml
Eric C Ames
```
ericcames@msn.com
