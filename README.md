Role Name
cs-cart role

A brief description of the role goes here.

Requirements
php7.4-fpm all extensions , nginx and database(mariadb) 

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
galaxy_info:
author: Manoj kumawat
description: This ansible role install  cs-cart for Debian.
company: "opsstation"

# If the issue tracker for your role is not on github, uncomment the
# next line and provide a value
# issue_tracker_url: http://example.com/issue/tracker

# Choose a valid license ID from https://spdx.org - some suggested licenses:
# - BSD-3-Clause (default)
# - MIT
# - GPL-2.0-or-later
# - GPL-3.0-only
# - Apache-2.0
# - CC-BY-4.0
license: license (GPL-2.0-or-later, MIT, etc)

min_ansible_version: 2.1

# If this a Container Enabled role, provide the minimum Ansible Container version.
# min_ansible_container_version:

#
# Provide a list of supported platforms, and for each platform a list of versions.
# If you don't wish to enumerate all versions for a particular platform, use 'all'.
# To view available platforms and versions (or releases), visit:
# https://galaxy.ansible.com/api/v1/platforms/
#
# platforms:
# - name: Fedora
#   versions:
#   - all
#   - 25
# - name: SomePlatform
#   versions:
#   - all
#   - 1.0
#   - 7
#   - 99.99

galaxy_tags: []
# List tags for your role here, one per line. A tag is a keyword that describes
# and categorizes the role. Users find roles by searching for tags. Be sure to
# remove the '[]' above, if you add tags to this list.
#
# NOTE: A tag is limited to a single word comprised of alphanumeric characters.
#       Maximum 20 tags per role.

dependencies: []
# List your role dependencies here, one per line. Be sure to remove the '[]' above,
# if you add dependencies to this list.


A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
