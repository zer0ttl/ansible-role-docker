ansible-role-docker
=========

This role installs docker and its dependencies.

Requirements
------------

- Debian based OS like Ubuntu.

Role Variables
--------------

- role_tags: There's a default tag named `docker`. You can add more if required.
- required_packages: Pre-requisites required for installation of docker.
- remove_docker_packages: List of packages that need to be cleaned off the system before attempting to install docker.
- install_docker_packages: List of packages required for installation of docker.
- print_debug: Set to `true` if you require debug tasks to run.

Dependencies
------------

- No other dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - ansible-role-docker

License
-------

BSD

Author Information
------------------

- Author: Sudhir Shirsath
