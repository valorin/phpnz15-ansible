## Ansible Playbook

This is a basic example project for my **Ansible, live on stage** talk at the
*New Zealand PHP Conference 2015*.

For more information: <http://stephen.rees-carter.net/talks/ansible-live>

## Instructions

1. Update `hosts` with the two hosts you wish to deploy the applications onto.
2. Rename the `host_vars/combination` and `host_vars/shoutbox` files to match the hosts you specified in `hosts`.
3. Update the `ansible_ssh_user` variables in the `host_vars/*` files, if required.
4. Run `ansible-playbook servers.yml`

*Note: this has been tested on Ubuntu 14.04 only.*
