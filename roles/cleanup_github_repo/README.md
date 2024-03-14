cleanup_github_repo
=========

This role will clean up are old insights cve remediation playbooks

Requirements
------------
```yaml
Access to the github repo
```
Role Variables
--------------
```yaml
software_repository: https://{{personal_access_token}}@github.com/ericcames/RedHatInsightsPlaybooks.git
local_repo: /var/tmp/github/RedHatInsightsPlaybooks
git_name: ericcames
git_email: ericcames@msn.com
personal_access_token: git_hub_token
```
Dependencies
------------

Example Playbook
----------------
```yaml
---
- name: Cleaning our repo
  hosts: localhost
  connection: local

  roles:

    - name: cleanup_github_repo
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
