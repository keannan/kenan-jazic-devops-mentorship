1. You need to know what the OSI model is
OSI model is model for network 7 layers 
2. What protocols are
Protocols are used for communication between devices and applications (depends of which layer of OSI is used)
3. IPv4 addressing (being able to create your own subnet), for example, if you have a CIDR block 10.0.0.0/24 and you are asked to create 2 subnets that belong to that CIDR block, where you will have 128 IP addresses available in each subnet you should be able to do subnetting manually using pen and paper.
Of course
10.0.0.0/25
10.0.0.128/25
but there will be only 126 IP addresses available since 
first one is for network address
and last one is broadcast address

4. Difference between private and public IPv4 addresses
Private IPv4 address are used in private networks 
10.0.0.0/8
172.16.0.0/12
192.168.0.0/16 
all other IPv4 addresses are public and used accross internet and can be accesses via internet 
private IPv4 addresses are not public routeable or accessible.

5. What is IPv6, why we need IPv6 and what is main difference between IPv4 and IPv6
IPv6 is new IP version of addressing. We need IPv6 because there is no more IPv4 addresses available for all hosts which use internet. 
IPv4 is 32bit addresses and IPv6 is 128bit addresses.
IPv4 is written in decimal in 4 octets
IPv6 is written in hex 
6. What is a client-server architecture
I know this concept but it is a lot of to write down :)
7. Who is the client and who is server
Client is every host who is accessing server resources
Server is host where are service is running
8. What is the TCP protocol
TCP protocol is 
9. What is HTTP protocol and why we are using it
HTTP protocol is L7 protocl used for accessing applications mostly
10. What is the main difference between TCP and UDP protocols
TCP is connection state protocol, connection needs to be established so packets will run 
UDP is connectionless protocol, connection does not need to be established, packets are flowing :)
11. What is FQDN
FQDN is Full Qualified Domain Name, (or DNS record for some host)
12. What is DNS, why do we need it, how it works
DNS is protocol which address IPv4/IPv6 adreses to domain names and reverse
When we browse for example google.com DNS translate google.com to IPv4 or IPv6 address of google.com host and router then route us to that server
13. What is VPN
VPN is Virtual Private Network mostly used to access from remtoe location to some other location safely across internet. There are a lot of VPN implementation types. I did all of them :)