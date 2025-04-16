# To do:
* signup for cisco networking academy
* courses in CNA have free materials which you can use to learn networking fundamentals


# Insights:
* I already know some linux, linux command line operations like ssh, scp, etc. through learning docker, docker compose, and using VMs in my previous usage of COAREs services in my undergrad dissertation, I already know using windows services by  

## learn the following
learn how data moves from one layer to another
layer 2 switching layer 3 routing
tcp ip model
subnetting
divide network into smaller ones efficeintly
vlance (how to traffic inside a network)
networking runs on protocols
protocol range from DNS, DHCP, BGP, OSPF, HTTP, HTTPS, FTTP, SSH
cisco networking academy for free courses
network+

## get certified
comptia+ certification
coptia all in one mike myers

CCNA (cisco certified network associate) 300$
neil anderson udemy course
cisco netowrking officail CCNA book

net+ certification 369$
professor youtube channel

## do projects
you will need to get your hands on hardware like routers using ethernet cables etc.

next step is building and configuring networks

this can either be done by 1 building a home lab itself which requires you to purchase routers, switches, and configure firewalls with these devices but 2 you can also virtualize building these networks themselves by using cisco's packet tracer application allowing you through diagrams connect stuff and what have you and build a network and configure a firewall etc. without having to do it in real life and purchasing shit.

hardware route:
Cisco catalyst 2960/2750 50$
cisco isr 2900 series 100$
extreme g2 layer 3 sswitch 200$
ex4300 series 100$
unified access point
palo alto 820 (used)

virtual app:
* cisco packet tracer
* gns3 (for real world setups)
* evneng


* oh so the IP address let's say of our host machine like when we `ipconfig` in cmd e.g.
```
Windows IP Configuration


Wireless LAN adapter Local Area Connection* 1:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Local Area Connection* 2:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :

Wireless LAN adapter Wi-Fi:

   Connection-specific DNS Suffix  . : bbrouter
   IPv6 Address. . . . . . . . . . . : <4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>
   Temporary IPv6 Address. . . . . . : <4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>
   Link-local IPv6 Address . . . . . : <4 chars of letters or digits>::<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>%<2 digits>
   IPv4 Address. . . . . . . . . . . : <[0-255]>.<[0-255]>.<[0-255]>.<[0-255]>
   Subnet Mask . . . . . . . . . . . : <[0-255]>.<[0-255]>.<[0-255]>.<[0-255]>
   Default Gateway . . . . . . . . . : <4 chars of letters or digits>::<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>:<4 chars of letters or digits>%<2 digits>
                                       <[0-255]>.<[0-255]>.<[0-255]>.<[0-255]>

Ethernet adapter Ethernet:

   Media State . . . . . . . . . . . : Media disconnected
   Connection-specific DNS Suffix  . :
```

184.145.50.9 for instance is actually an the decimal representation of each of these 4 values in the ip address. E.g. because when these are converted to binary it becomes 0000 0000.0000 0000.0000 0000.0000 0000 and what do we have when we have 8 binary values we have octets. And each value of an octet recall exponentiates by 2 so starting from the first binary digit of an octet we have 
1 then to the second binary digit we have 2 then to the third wee have 4 then 8 and then 16 32 64 then 128
```
2 ** 0 = 1 * 0
2 ** 1 = 2 * 1
2 ** 2 = 4 * 0
2 ** 3 = 8 * 0
2 ** 4 = 16 * 1
2 ** 5 = 32 * 1
2 ** 6 = 64 * 0
2 ** 7 = 128 * 1
---------------------
0 + 2 + 0 + 0 + 16 + 32 + 0 + 128 = 178
```
therefore 178 in binary is 0100 1101 or as an octet


## after learning, certification, and creating projects in your job search you need to start either in the following roles before even landing a junior network engineering role:
IT helpdesk analyst
IT helpdesk 
ISP (internet service provider) technician
IT support technician
desktop support technician
IT technician


### Helpdesk tools you can use for automation and ease:
- Windirstat for checking ehich files are too big

### Scenarios user faces that you'll need to fix:
Installing drivers for videos sound, graphics
Media players not having sound or not playing is a driver issue
Cant connect to the Internet not connecting maybe a problem with Ethernet cable, maybe a restart is im order so ask user to save his work before restarting 
Internet is slow, this maybe due to chrome or any browser having too much tabs open i.e. 20 and not clearing a profiles cache
Users not being able to send emails can be due to the storage limit of a google account and you cant send or receive emails because of the cap. Another can be because of having slow or no internet.
This program is crashing.
I can't open this file.
I need help installing a software update.
My printer isn't working.
My computer won't boot.
I have a blue screen error
My computer won't let me log in. You have to reboot and enter safe mode
I forgot my password. You have to login as admin and change the password
My account isn't working.

Remember the times when you had to F11 during OS boot and enter the BIOS basic input output system interface

In windows 11 youd be pressing f2, f10, or delete to enter bios interface

learning to install drivers for printers, mouses, keyboards, microphones, headphones

installing directX for applications/software that may use it as a dependenciy. Just like installing packages in python which may have dependencies to other packages softwares may also require other software in order to work. I.e. in order to run a C/C++ compiler you need mingw installer and have the gcc/g++ packages installed

in order to run a python app you need python3 installed
in order to run npm, choco, react, svelte you need node.js installed in your machine

in order to run conda you need to have conda installed in your machine which may have missing dll files also that you need to add.

Once these are all installed you'd have to their paths to the PATH variable of the system environment variables

# Articles, videos, papers, etc.
* networking fundamentals: https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi&index=1
