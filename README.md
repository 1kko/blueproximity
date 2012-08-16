blueproximity
=============
Bash version of blueproximity

Many codes are from Internet. Only thing I did was copy and paste and scrub some things off.

- Copied from Steven on http://gentoo-wiki.com/Talk:TIP_Bluetooth_Proximity_Monitor
- Modified By Jamie Paton 
- Modified By Michele Marcucci http://www.michelem.org
- Modified By Mone http://www.simonefabiano.com
- Modified by ikko http://1kko.com https://github.com/1kko/blueproximity

once you have run the script,
default configuration is stored in "<your home dir>/.blueproximity/blueproximity.conf"


Requirement
----
- hcitool
- rfcomm
- l2ping


Configuration
----
turn on your bluetooth device and set to pairing mode.

run blueproximity in prompt
 ./blueproximity

it scan near bluetooth devices, and display mac address.
when script prompts enter your Phone's bluetooth MAC address in the format of 00:12:34:56:78:9A
 Please Enter your Device's Bluetooth MAC Address: 00:12:34:56:78:9A

it will generate configuration file to <your homedir>/.blueproximity/blueproximity.conf

 your config is stored to <your homedir>/.blueproximity/blueproximity.conf

 to check out configuration, type:

   cat <your homedir>/.blueproximity/blueproximity.conf


now you can either run again to see if it works, or
you can edit configuration file and script itself for your taste.


Installation
----
you can make run the script when you login.
If you are using Ubuntu:
go to System Setting > Start Up Applications > Add 
