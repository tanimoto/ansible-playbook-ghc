# ansible-playbook-ghc

Ansible Playbook for installing the Glorious Haskell Compiler (GHC)
on Ubuntu/Debian.


## Assumptions

This playbook has been tested on Ubuntu 13.04 with GHC 7.6.3.


## Instructions

1. Install Ansible

2. Clone this repository

3. Adjust `vars/main.yml` if needed

4. Run the playbook:

    $ ansible-playbook -i hosts main.yml


## Acknowledgments

Inspired by jgrowl's collection of Ansible Playbooks.
