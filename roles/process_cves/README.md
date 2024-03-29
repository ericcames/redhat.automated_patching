process_cves
=========

This role will patch cves on target machine

Requirements
------------
```yaml
RHEL Servers with Insights client enabled
Software repo with token
```
Role Variables
--------------
```yaml
software_repository: https://{{personal_access_token}}@github.com/ericcames/RedHatInsightsPlaybooks.git
local_repo: /var/tmp/github/RedHatInsightsPlaybooks
git_name: ericcames
git_email: ericcames@msn.com
job_template_id: 165
```
Dependencies
------------
```yaml
```
Example Playbook
----------------
```yaml
---
- name: Process CVES
  hosts: localhost
  connection: local

  roles:

    - name: process_cves
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
