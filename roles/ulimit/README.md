ulimit
===========

Alteração de ulimit 

Example Playbook
----------------
  hosts: group_server
  roles:
  - { role: ulimit, user_limits: USER, limits_soft: "{{ USER_limits_soft }}", limits_hard: "{{ USER_limits_hard }}"}


Author Information
------------------
Geovana Possenti de Souza - geovana.possenti@gmail.com
