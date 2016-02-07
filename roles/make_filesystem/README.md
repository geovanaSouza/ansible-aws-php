Make Filesystem
===========

Manipulação de FileSystem / Criação e configuração ponto montagem

Example Playbook
----------------
  hosts: group_server
  roles:
  - { role: make_filesystem, fs_type: "{{ fs_type_VARIABLE }}", fs_device: "{{ fs_device_VARIABLE }}", fs_directory: "{{ fs_directory_VARIABLE }}"}


Author Information
------------------
Geovana Possenti de Souza - geovana.possenti@gmail.com
