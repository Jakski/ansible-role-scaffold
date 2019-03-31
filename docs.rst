ansible-role-scaffold
================================================================================

Ansible role to scaffold new role project.

Variables
--------------------------------------------------------------------------------

scaffold_name

   Role's name

scaffold_author

   Role's author

scaffold_destination

   Role's destination directory

scaffold_description

   Role's short description

scaffold_platforms

   Platforms supported by role

Examples
--------------------------------------------------------------------------------

.. literalinclude:: molecule/default/playbook.yml
   :language: yaml

Documentation
--------------------------------------------------------------------------------

Compile::

   $ pip3 install -r requirements.txt
   $ make man

View::

   $ man ./docs/man/ansible-role-scaffold.1
