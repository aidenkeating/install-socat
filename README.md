Install socat on macOS
=========

Install `socat` without using package managers like `brew`.

Requirements
------------

* `curl`
* `bsdtar`

Role Variables
--------------

* `archive_location`
* `tmp_dir`
* `install_dir`

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: aidenkeating.install-socat }

License
-------

MIT

Author Information
------------------

Aiden Keating <akeating@redhat.com>
