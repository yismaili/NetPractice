# NetPractice
This project is a general practical exercise to let you discover networking.

# History of Networking
omputer networking as we know it today may be said to have gotten its start with the Arpanet development in the late 1960s and early 1970s. Prior to that time there were computer vendor “networks” designed primarily to connect terminals and remote job entry stations to a mainframe.

# What is Networking
 A network consists of two or more computers that are linked in order to share resources (such as printers and CDs), exchange files, or allow electronic communications. The computers on a network may be linked through cables, telephone lines, radio waves, satellites, or infrared light beams.
 
Two very common types of networks include:  
 # LAN or Local Area Network : 
A Local Area Network (LAN) is a network that is confined to a relatively small area. It is generally limited to a geographic area such as a writing lab, school, or building
 # WAN or Wide Area Network :
Wide Area Networks (WANs) connect networks in larger geographic areas, such as Florida, the United States, or the world. Dedicated transoceanic cabling or satellite uplinks may be used to connect this type of global network

![download](https://user-images.githubusercontent.com/69278312/189350638-787f04fd-d05f-485c-ab02-59cc162c0b9e.png)

# Subnet Mask Definition

Every device has an IP address with two pieces: the client or host address and the server or network address. IP addresses are either configured by a DHCP server (Dynamic Host Configuration Protocol) or manually configured (static IP addresses). The subnet mask splits the IP address into the host and network addresses, thereby defining which part of the IP address belongs to the device and which part belongs to the network.

![1_1KIknnLKXpXptCyVRf6KCQ](https://user-images.githubusercontent.com/69278312/189372521-5947ddd2-07d2-4333-b437-313a5b7bb443.png)

# What is Subnet Mask

A subnet mask is a 32-bit number created by setting host bits to all 0s and setting network bits to all 1s. In this way, the subnet mask separates the IP address into the network and host addresses.

# IP Address and Subnet Mask

A 32-bit IP address uniquely identifies a single device on an IP network. The 32 binary bits are divided into the host and network sections by the subnet mask but they are also broken into four 8-bit octets.

Because binary is challenging, we convert each octet so they are expressed in dot decimal. This results in the characteristic dotted decimal format for IP addresses—for example, 172.16.254.1. The range of values in decimal is 0 to 255 because that represents 00000000 to 11111111 in binary.

<img width="917" alt="Screen Shot 2022-09-09 at 4 07 01 PM" src="https://user-images.githubusercontent.com/69278312/189382567-52f9f9d3-9203-4409-bbe4-2e59b7a435f2.png">

# IP Address Classes and Subnet Masks

A Class A subnet mask reflects the network portion in the first octet and leaves octets 2, 3, and 4 for the network manager to divide into hosts and subnets as needed. Class A is for networks with more than 65,536 hosts.

A Class B subnet mask claims the first two octets for the network, leaving the remaining part of the address, the 16 bits of octets 3 and 4, for the subnet and host part. Class B is for networks with 256 to 65,534 hosts.

In a Class C subnet mask, the network portion is the first three octets with the hosts and subnets in just the remaining 8 bits of octet 4. Class C is for smaller networks with fewer than 254 hosts.

Class A, B, and C networks have natural masks, or default subnet masks:

Class A: 255.0.0.0
Class B: 255.255.0.0
Class C: 255.255.255.0
You can determine the number and type of IP addresses any given local network requires based on its default subnet mask.

An example of Class A IP address and subnet mask would be the Class A default submask of 255.0.0.0 and an IP address of 10.20.12.2.

# Network Addressing

The standard modern network prefix, used for both IPv6 and IPv4, is Classless Inter-Domain Routing (CIDR) notation
<img width="687" alt="Screen Shot 2022-09-09 at 5 16 18 PM" src="https://user-images.githubusercontent.com/69278312/189395512-f4409fbc-1fbc-4036-b5bc-7a9e83196778.png"> 
# What Is a Subnet Mask Calculator

Here are some of the most common varieties of IP subnet mask calculator:

A IPv6 IP Subnet Calculator maps hierarchical subnets.
An IPv4/IPv6 Calculator/Converter is an IP mask calculator that supports IPv6 alternative and condensed formats. This network subnet calculator may also allow you to convert IP numbers from IPv4 to IPv6.
An IPv4 CIDR Calculator is a subnet mask adjustment and Hex conversion tool.
An IPv4 Wildcard Calculator reveals which portions of an IP address are available for examination by calculating the IP address wildcard mask.
Use a HEX Subnet Calculator to calculate the first and last subnet addresses, including the hexadecimal notations of multicast addresses.
A simple IP Subnet Mask Calculator determines the smallest available corresponding subnet and subnet mask.
A Subnet Range/Address Range Calculator provides start and end addresses.


