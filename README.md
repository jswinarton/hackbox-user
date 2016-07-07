hackbox-user
=========

An Ansible role that provisions an Ubuntu box with a full user ready for hacking. Sort of an extension for [my dotfiles](https://github.com/jswinarton/dotfiles).


Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: "hackbox-user", username: "jeremy" }

