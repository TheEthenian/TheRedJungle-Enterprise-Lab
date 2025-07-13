TheRedJungle [Lab]

A replica of a large hotel chain designed to be a RedTeam Lab

Compises of 20 vms of which some have individual purpose where as others serve 2 tasks for the sake of resources , they all you either almalinux-minimal server or ubuntu server.

Most of the VMs have about 3 container for the api gateway , vault and the backend api technology

OPNsense is to be at the forefront of this 'TheRedJungle' and is connects all the isolated internal networks and provides them with outside world access or internet access 

There comprises 7 isolated libvirt networks wormholed into OPNsense and OPNses uses a nat network from libvirt.

The is expected plethora and laborynth of apis and interconnectivity between various vms some recieve calls almost every time thus the 'core_netork'.

To pleclude redundancy one windows10 os was used as the POS terminal, admin and staff work station, also as the BMS workstation.

Kali was the attacker/operation vm [Just for the sakes of mentioning it]


The following are the vms that use Almalinux-minimal os:

Domain_controller & DNS server
DHCP & Firewall server
Application server
IP Telephony system server
Web server
Reverse_Proxy_Load_Balancer
VPN concentrator
File server
HR & Finance server
Payment Gateway
Access control server
Guest room management systems
Energy management unit & BMS backend system
Email Gateway
Single PoP CDN

The following are the vms that use Ubuntu-minimal os:

Centralised logging and monitoring server
VMS server
IoT device simulation







