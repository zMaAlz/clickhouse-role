Clickhouse-role
=========

Роль для Ansible 2.10 и новее для установки СУБД Clickhouse на CentOS. 

Requirements
------------

Роль работает только на дистрибутивах CentOS.

Role Variables
--------------

clickhouse_version - определяет версию clickhouse для установки

Dependencies
------------

Иные зависимости не требуются. 

Example Playbook
----------------

Пример использования:

---
- name: Install Clickhouse
  hosts: clickhouse
  roles:
    - clickhouse-role


License
-------

MIT

Author Information
------------------

[Git](https://github.com/zMaAlz/clickhouse-role)

