packages-gstreamer-plugins
========

An [ansible role](https://galaxy.ansibleworks.com/list#/roles/213) to install
additional multi-media plugins and libraries to enable mp3 playback and mp4
video watching (etc.) using standard programs such as Firefox and Totem.

    ---
    - hosts: localhost

      roles:
        - groks.packages-gstreamer-plugins

Requirements
------------

An installation of [Fedora](https://fedoraproject.org/get-fedora).

Role Variables
--------------

None.

Dependencies
------------

This role depends on the
[groks.repo-extra](https://galaxy.ansibleworks.com/list#/roles/202) role which
enables the package repositories where most of these plugins are found.

License
-------

BSD
