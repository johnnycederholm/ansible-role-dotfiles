Dotfiles
=========

Ansible role for setting up dotfiles hosted in Git repo


Example Playbook
----------------

    - hosts: desktop
      roles:
         - name: Setup dotfiles
           role: dotfiles
           vars:
            dotfiles_repo: https://github.com/owner/dotfiles.git
            dotfiles_dest: "/home/{{ ansible_user }}/.dotfiles" 

License
-------

MIT