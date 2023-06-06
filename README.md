Role Name
=========

Роль для создания и удаления программного массива в Linux.


Role Variables
--------------

Для создания массива в файле defaults/main.yml - state: 'present'
Для удаления массива defaults/main.yml - state: 'absent'



Example Playbook
----------------

Пример playbook

- hosts: all
  remote_user: yarikuz
  roles:
    - mdadm_create_delete

inventory

  [all]
    server1 ansible_host=192.168.100.165

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
