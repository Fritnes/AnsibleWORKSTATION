Role "Workstation"
=========

Install apps for workstation

Example Playbook
----------------

    - hosts: servers
      roles:
	- { role: AnsibleWORKSTATION, when: ansible_system == 'Linux' }

Author Information
------------------

fritnes
https://github.com/Fritnes/AnsiblePI-HOLE
