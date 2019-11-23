# Security Lab

This project is a simple Vagrant based security lab. It's a quick and easy way
to spawn VMs to exploit and play with.

The beauty of this project is that it works on Linux, Mac & Windows through the
power of virtual machines and [Vagrant](https://www.vagrantup.com/).

## Setup

First, make sure that you have the prerequisites.

- [Vagrant](https://www.vagrantup.com/)
- A Hypervisor

  Vagrant supports a [few hypervisors](https://www.vagrantup.com/docs/providers/)
  (they call them providers).

  I recommend [VirtualBox](https://www.virtualbox.org/). This is what I test &
  develop this project with and I find that the community that provides vagrant
  boxes usually supports VirtualBox.

Second, download the content of this repo. You can either:

- Clone it with `git`:

  ```sh
  git clone https://github.com/dotboris/security-lab.git
  ```

- Download the source code [archive](https://github.com/dotboris/security-lab/archive/master.zip) and Extract it.

## Usage

1.  Open a terminal in the directory where you cloned / downloaded this project
1.  Start the VMs you want to play with:

    ```sh
    vagrant up {vm_names...}
    ```

    You can see the different available [VMs](#vms) the [VMs](#vms) section
    below.

1.  Find the target VM ips

    TODO: How do we do this?

1.  Start hacking

    If you don't have tools prepared already, this repo lets you start up a Kali
    Linux VM. (TODO: document Kali VM)

## VMs
