Basic Server Setup
==================

These scripts deal with the initial set-up of my user accounts on several
servers. To deploy/update the settings run:

    ansible-playbook -k -K -i hosts server-user-setup.yml [--limit host-or-group]
