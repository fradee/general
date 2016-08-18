# Ansible Role: general

## Install by default if not defined other:
        curl
        acl
        git
        mc
        htop
        gzip

## Role Variables

Available variables are listed below with its default values.

     fradee_timezone: Europe/Kiev
     fradee_packages:
         - curl
         - acl
         - git
         - mc
         - htop
         - gzip
     fradee_repos:
         - ppa:ondrej/php

## Example Playbook

	- hosts: database
      become: yes
      roles:
        - fradee.general
        

## License

MIT / BSD

## Notes

This is my first playbook it is a beta version and can be improved, please help me to improve and fix bugs for this playbook.

Thanks.
