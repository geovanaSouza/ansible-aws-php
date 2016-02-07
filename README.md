Ansible PHP
===========

Configura um servidor PHP em uma conta na Amazon AWS

Requirements
------------

O playbook foi homologado no Sistema Operacional Ubuntu 14.04

O(s) servidor(es) deverá(ão) ter um disco de 10 Gb atachado

O arquivo inventory/hosts_example deverá ser alterado para informações de acordo com informações dos servidores a serem configurados

Copie a chave com permissão de acesso ssh ao servidor para o diretório keys/ ou altere o parâmetro ansible_ssh_private_key_file direcionando para a localização da chave

O servidor de onde partirá o a configuração deverá possuir o aws CLI instalado e configurado

Ansible Version
----------------

A versão do Ansible deverá ser igual ou superior à 2.0. Caso a versão instalado no servidor origem da configuração seja menor, basta executar o playbook de pré-requisitos, antes de iniciar a instalação

ansible-playbook -i inventory/hosts_example playbooks/prereq.yml

Example Execution
----------------

ansible-playbook -i inventory/hosts_example playbook/config.yml

Author Information
------------------
Geovana Possenti de Souza - geovana.souza@nexxera.com
