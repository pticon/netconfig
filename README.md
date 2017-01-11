netconfig
=========

Configure network interfaces on a GNU/Linux system.

Usage
-----
```
Display or set network informations
usage: netconfig [options] [interface]
options:
	--help  |-h           : display this and exit
	--dhcp  |-d           : dhcp mode
	--eth   |-e <ethaddr> : set MAC address
	--ip    |-i <ip>      : set ip address
	--mask  |-m <mask>    : set ip mask address
	--bcast |-b <addr>    : set broadcast address
	--gw    |-g <gw>      : set the default gateway
	--ns    |-n <server>  : set the name server
	--save  |-s           : save the configuration
	--csv   |-c           : output display as a CSV
	--all   |-a           : consider all of the interfaces
```

Example
-------
```
./netconfig -ac
```
netconfig will display in a CSV format about if (interface),
plug (state), dyn (dynamic), mac (mac address), ip (IP address),
mask (network mask), bcast (broadcast address), gw (gateway)
and ns (Name server).

License
-------
netconfig is licensed uder the MIT license.
