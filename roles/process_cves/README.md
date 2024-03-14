get_aws_instance_info
=========

This role will get all AWS Machine Instance Info.

Requirements
------------
```yaml
Amazon Web Console Account
Amazon Web Services Credential in Ansible Automation Platform
```
Role Variables
--------------
```yaml
region: us-west-1
servername: Linux Web Server
my_email_address: eames@redhat.com
```
Dependencies
------------
```yaml
amazon.aws
```
Example Playbook
----------------
```yaml
---
- name: Get Amazon Machine info
  hosts: localhost
  connection: local

  roles:

    - name: get_aws_instance_info
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
