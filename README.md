rbenv_osx
================

Ansible role tpara configurar o rbenv no OS X.

Requisitos
------------
[Homebrew](http://brew.sh/) deve ser instalado.

Role Variables
--------------
-   cs-tiago-almeida.rbenv

Role Variables
--------------
-

Exemplo de um Playbook
----------------
---
- name: Install Server

  hosts: localhost
  gather_facts: no
  become_user: root

  roles:
    - { cs-tiago-almeida.rbenv }

Licença
-------
MIT

Author Information
------------------
[Tiago de Almeida Francisco] (repo)
