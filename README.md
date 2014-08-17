Ansible Playbook:: Ross Timson Workstation
==========================================

This Playbook sets up my development workstation / laptop.

Platforms
---------

* Fedora 20

Usage
-----

### Manual Play

Install Ansible

```
yum install -y ansible
```

Clone and run Playbook

```
git clone https://github.com/rosstimson/ansible-rosstimson-workstation.git
cd ansible-rosstimson-workstation

# Run as normal user - it will prompt for sudo password
ansible-playbook workstation.yml -K
```

Todo
----

- [ ] Automated installer script.
- [ ] Setup a Mac.
- [ ] Find a way to install gems under chruby.

Development
-----------

* Source hosted at [GitHub][repo]
* Report issues/questions/feature requests on [GitHub Issues][issues]

License and Author
------------------

Author:: [Ross Timson][rosstimson]
<[ross@rosstimson.com](mailto:ross@rosstimson.com)>.

License:: Licensed under [WTFPL][wtfpl].


[rosstimson]:         https://rosstimson.com
[repo]:               https://github.com/rosstimson/ansible-rosstimson-workstation
[issues]:             https://github.com/rosstimson/ansible-rosstimson-workstation/issues
[wtfpl]:              http://www.wtfpl.net/
