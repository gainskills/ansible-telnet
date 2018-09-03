# ansible-telnet

By default, Ansible module will retrieve username/password value from playbook file: telnet block.
Since the fields are supported by inventory already, and the part also was highlight, I custome it and test it.

Back your file and update it to /site-packages/ansible/plugins/action/telnet.py

Note:
the setting: 
connection: local 
in playbook will cause ansible use you local user.
