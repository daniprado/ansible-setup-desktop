# ansible-setup-desktop

Ansible role to setup my desktop environment.  This works on Ubuntu and Arch Linux based linux systems.

      ## Usage

      Create a playbook with your tasks, and include the role. You will need to provide 2 variables
      - user_name
      - dotfiles_url

      The simplest configuration therefore consists of:

      ```yaml
      - name: Simple Example
        hosts: localhost
        roles:
          - role: ansible-setup-desktop
        vars:
          user_name: dani
          dotfiles_url: https://github.com/daniprado/dotfiles.git
      ```

