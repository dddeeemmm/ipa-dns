ipa-dns
=========

    Manage Free IPA DNS zones and records

Requirements
------------

    DNS permissions for account

Role Variables
--------------

    ipa_username_default: ''        # [not required] username for default sys account
    ipa_password_default: ''        # [not required] password for default sys account
    ipa_hosts: []                   # [required] ipa servers dictionary
    ipa_dns_zone: ''                # [required] setup zone /vars/{{ ipa_dns_zone }}.yml
    ipa_dns_records: []             # [not required] dns records dictionary


Example Playbook
----------------

    /tests/test.yml

Example Run
----------------

    ansible-playbook playbook.yml

License
-------

    MIT

Author Information
------------------

    Dmitrij Petrov
    https://github.com/dddeeemmm
