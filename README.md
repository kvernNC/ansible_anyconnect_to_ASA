# ansible_anyconnect_to_ASA

A simple playbook that let you create Anyconnect Profile on an ASA, based on few informations given by .yml files.

How to:

1°) edit hosts file

2°) edit Conventions/*.yml according to your needs

3°) edit add_anyconnect_group.j2 and add_ACL.j2 according to your standard

4°) run it: ansible-playbook playbook1.yml


This is idempotent. 
