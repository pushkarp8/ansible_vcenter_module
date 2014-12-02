vcenter_module
===================

ansible module to do various vcenter tasks, such as clone a vm, reconfigure a vm, snapshot a vm, and set permissions on a vm. This is my first attempt at an ansible module, and was originally crafted to meet my organizations needs (to fill in where the shipped vcenter_module lacked). 

I've included some example playbooks for various tasks, I understand that the inbuilt documentation in the module is lacking quite a bit. I will need to rewrite this someday.

Most of the vars you'll need are in group_vars/all -- others will be defined in the playbooks
