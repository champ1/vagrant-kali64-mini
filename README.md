==============

A « vanilla » Kali 64 vagrant box, without any tools on it.

### Raison d'être
* Keep your pentesting/hacking environment clean, separate from your main system.
* Automate boring tasks; manage your configuration files with Puppet/Chef.
* Open up the tools; ease security software development using Kali. 
* Empower users; forces us to understand what tools we use, what workflow we like, what features we need.

### Info
* Small download size (~304MB) 
* Small memory footprint (~64MB)
* Accessed mainly from the CLI, no GUI.
* Provides userspace credentials (vagrant:vagrant)
* VirtualBox Guest Additions 4.3.8
* Puppet 3.4.3
* Chef 11.10.4-1

### Usage 

    vagrant up

    vagrant ssh

    # and finally 
    vagrant destroy -f

**IP Address**

    6.6.6.6

