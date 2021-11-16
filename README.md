Kibana role
=========

Роль для установки Kibana на хостах с ОС: Debian, Ubuntu, CentOS, RHEL.

Requirements
------------

Поддерживаются только ОС семейств debian и EL.

Role Variables
--------------

| Variable name | Default | Description |
|-----------------------|----------|-------------------------|
| kibana_version | "7.15.2" | Параметр, который определяет какой версии kibana будет установлен |

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: mnt-homeworks-ansible }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
 
Aliaksandr Molchan