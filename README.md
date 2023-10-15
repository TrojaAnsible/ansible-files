Role Name
=========

used to deploy mandatory files into /usr/local for new server installations

* Repository URL: [ansible-files](https://github.com/TrojaAnsible/ansible-files)

Requirements
------------


Role Variables
--------------
| defaults variable | description |
|-------------------|-------------|
| my_user                   |user name (for permissions)|
| base_git_dir              |checkout directory|
| github_url                |github domain name https://github.com|
| github_rawurl             |github domain name for raw file download|
| github_user               |github user|
| github_orga               |github organisation|
| github_scripts_repo_name  |name of github repository|
| git_files_repo            |full repo url, built from above variables|
| usr_local_etc_files       |files to deploy to /usr/local/etc|
| usr_local_bin_files       |files to deploy to /usr/local/bin|


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
