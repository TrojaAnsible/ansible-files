Role Name
=========

used to deploy files into /usr/local to provide new users with a standard set of config files

Requirements
------------


Role Variables
--------------

base_git_dir: /opt/git

github_url: 'https://github.com'

github_rawurl: 'https://raw.githubusercontent.com'

github_user

github_orga

github_scripts_repo_name: 'scripts-collection'

git_files_repo: '{{ github_url }}/{{ github_orga }}/{{ github_scripts_repo_name }}.git'


usr_local_etc_files

usr_local_bin_files


Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-files }

License
-------

This project is licensed under the Attribution-NonCommercial-ShareAlike 4.0 International License - see the [LICENSE.md](LICENSE.md) file for details

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
