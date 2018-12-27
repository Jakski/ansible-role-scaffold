ansible-role-scaffold
*********************

Ansible role to scaffold new role project.


Variables
=========

scaffold_name
   Role's name.

   Default: undefined

scaffold_author
   Role's author.

   Default: undefined

scaffold_destination
   Role's destination directory.

   Default: undefined

scaffold_description
   Role's short description.

   Default: undefined


Examples
========

   ---
   - hosts: instance
     tasks:
       - import_role:
           name: scaffold
         vars:
           scaffold_destination: "{{ ansible_facts.user_dir }}/example"
           scaffold_name: example
           scaffold_author: John Doe
           scaffold_description: Some Ansible role


Documentation
=============

Compile:

   $ pip3 install -r requirements.txt
   $ make man

View:

   $ man ./docs/man/ansible-role-scaffold.1
