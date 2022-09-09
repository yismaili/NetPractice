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
