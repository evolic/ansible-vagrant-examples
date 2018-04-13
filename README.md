# Ansible Vagrant Examples

This repository contains a collection of example virtual machines running various applications. The VMs are created via Vagrant and provisioned via Ansible.

You can `cd` into any of the included directories and run `vagrant up`, and a generic Linux VM will be booted and configured in a few minutes. You just need to install [Vagrant](http://vagrantup.com/), [VirtualBox](https://www.virtualbox.org/), and [Ansible](http://www.ansible.com/). View the included README.md file in any of the subdirectories to find out more about the particular VM.

All of these examples use a combination of [roles I've added to Ansible Galaxy](https://servercheck.in/blog/using-ansible-galaxy), and were created to help demonstrate Ansible's simplicity and flexibility.

Read more about Ansible and how I use it to manage infrastructure in [Ansible for DevOps](https://www.ansiblefordevops.com/), a book written by Jeff Geerling.

# VMs/Apps Currently Present

  - **RabbitMQ** (`rabbitmq` - mesage broker)

## License

MIT license.

## Author Information

Created in 2018 by [Tomasz Kuter](http://tomaszkuter.com/), based on work of [Jeff Geerling](https://www.jeffgeerling.com/), author of [Ansible for DevOps](https://www.ansiblefordevops.com/).

