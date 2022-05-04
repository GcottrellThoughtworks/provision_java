# Provisioning Java With Ansible
This playbook will provision Java for MacOS and Linux(Ubuntu, Debian and CentOS)

# Installation // Setup
Please see linked documentation for installing Ansible on your workstation: https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html

Once Ansible is installed, make sure you are able to ssh into your hosts as ansible will need this. 

# Using this Repo

Once you have Ansible setup on your workstation, you can clone this repo and run the playbook to provision Java on your remote hosts.

# Using this playbook locally

If you want to use this playbook locally (either from your workstation or host), you can run this command ```sudo ansible-pull -U https://github.com/GcottrellThoughtworks/provision_java_locally.git``` which will run the local version of this playbook. Please see the ReadME before running. 

# Repo Purpose

This repo is meant to be used to provision your hosts, so please see [provision_java_locally](https://github.com/GcottrellThoughtworks/provision_java_locally) if you are looking to run this playbook on your workstation or host locally.
