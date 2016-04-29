# Ansible Role: general

Ansible playbook to install general order applications:
        curl
        git
        wget
        python-software-properties
        mc
        htop
        gzip
        build-essential

## Role Variables

Available variables are listed below with its default values.

	development: true
    timezone: "Europe/Kiev"

## Example Playbook

	- hosts: database
      become: yes
      roles:
        - general
        - Xobb.percona

## License

MIT / BSD

## Notes

This is my first playbook it is a beta version and can be improved, please help me to improve and fix bugs for this playbook.

Thanks.
