Role Name
=========

 This role will take mongo backup and upload in s3 bucket


Role Variables
--------------
backup_dir: "/opt/backup"

buket_name: "opstree"

aws_dir_name: "backupmongo"

userName: "opstree"

passWd: "opstree"

password_less_login: false

password_login: true

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: mybb_hosts
      roles:
         - { role: sandy724.MyBB }

License
-------

BSD

Author Information
------------------
www.opstree.com

blog.opstree.com


