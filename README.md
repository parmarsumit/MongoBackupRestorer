Role Name
=========

This role takes mongodb backup including all cases(Full, Particular, Collection) and uploads it to S3 bucket


Role Variables
--------------
mongo_backup_dir: "/opt/backup"

s3_buket_name: "redcrackle"

aws_dir_name: "backupmongo"

mongo_database_username: "opstree"

mongo_database_passwd: "opstree"

mongo_database_name: "admin"

mongo_collection_name: "people"

password_less_login: false

password_login: false

backup_for_spaecfice_database: false

backup_for_spaecfice_collection: true

Here True or False must be provided according to users requirement

For example

If database is authenticated with password use false in password_less_login and likewise

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


