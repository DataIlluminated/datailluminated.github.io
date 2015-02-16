# datailluminated.github.io

Informational site for Data Illuminated.

# Vagrant

This project is setup to support [Vagrant](https://www.vagrantup.com/) for development with provisioning through [ansible](http://www.ansible.com/home).  Ansible works on windows by using JJG-Ansible-Windows bat script to run from inside the vagrant instance.

## Jekyll Serve in Vagrant

Port forwarding is setup in the vagrant file to map guest: 4000 to host: 4000

**important** - to serve through jekyll under Vagrant you need to set the host property to 0.0.0.0

  `jekyll serve --host 0.0.0.0`
