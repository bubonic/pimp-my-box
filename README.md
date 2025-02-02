
# pimp-my-box

This is a fork of the original **pimp-my-box** repo. It includes a working version for Ubuntu 20.04. 

### Ubuntu 20.04
We suggest as **ansible-playbook** runs, that after creating the **rtorrent** user, you log in or **su** to that user and install **pip** for **python2**. You can do this by:

```
curl https://bootstrap.pypa.io/pip/2.7/get-pip.py --output get-pip.py
python2 get-pip.py
```

With the modifications of dependencies made in this fork, we have it working on both *client/workstation* and *server* of Ubuntu version 20.04. 

We have tested it and all seems to install with minor complications. 


:warning: | Read the docs regarding the migration to Ansible 2 and ruTorrent 3.9! Report any problems to Gitter or issues (rutorrent setup was tested on Bionic)!
---: | :---

![logo](https://raw.githubusercontent.com/pyroscope/pimp-my-box/master/images/pimp-my-box.png)
[![issues](https://img.shields.io/github/issues/pyroscope/pimp-my-box.svg)](https://github.com/pyroscope/pimp-my-box/issues)
[![travis](https://api.travis-ci.org/pyroscope/pimp-my-box.svg)](https://travis-ci.org/pyroscope/pimp-my-box)

Automated install of [rTorrent-PS](https://github.com/pyroscope/rtorrent-ps) etc. via
[Ansible](http://docs.ansible.com/).

The playbooks in the ``pimp-my-box`` repository will install ``rTorrent-PS``, ``pyrocore``, and related software
onto any remote dedicated server or VPS with ``root`` access, running Debian or a Debian-like OS.

**See the [main documentation](http://pimp-my-box.readthedocs.io/) on how to install and use this.**

To get in contact and share your experiences with other users of *PyroScope*,
join the [rtorrent-community](https://gitter.im/rtorrent-community/) channel
[pyroscope-tools](https://gitter.im/rtorrent-community/pyroscope-tools) on Gitter.


## References

### Server Hardening

 * [Secure Secure Shell](https://stribika.github.io/2015/01/04/secure-secure-shell.html)
 * https://github.com/sfromm/ansible-rkhunter
