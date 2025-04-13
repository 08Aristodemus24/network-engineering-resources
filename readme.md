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

# Articles, videos, papers, etc.
* networking fundamentals: https://www.youtube.com/watch?v=bj-Yfakjllc&list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi&index=1
