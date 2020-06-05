# 42-netwhat-project

The project is an introduction to network problematics

1. What is an **IP address**

   An IP address is a number that uniquely identifies every host on an IP network. IP addresses are 32-bit binary numbers ~ 4 billion unique host addresses can exist throughout the Internet. The primary purpose of Internet Protocol (IP) is to enable communications between networks. As a result, a 32-bit IP address consists of two parts:
   * **The network ID** (or network address): Identifies the network on which a host computer can be found.
   * **The host ID** (or host address): Identifies a specific device on the network indicated by the network ID.

   IP addresses are usually represented in a format known as dotted-decimal notation. In dotted-decimal notation, each group of eight bits — an octet — is represented by its decimal equivalent.

2. What is a **Netmask**
3. What is the **subnet of an IP with Netmask**
4. What is the **broadcast address of a subnet**
5. What are the **different ways to represent an ip address** with the Netmask
6. What are the differences between **public** and **private** IPs
7. What is a **class** of IP addresses

   The IP protocol defines five different address classes: A, B, C, D, and E.

| Class         | first bits    | --            | Networks     | Hosts        |
|:-------------:|:-------------:|:-------------:|:------------:|:------------:|
| A             | 0xxx          | 1-126.x.y.z   | 126          | 16,777,214   |
| B             | 10xx          | 128-191.x.y.z | 16384        | 65534        |
| C             | 110x          | 192-223.x.y.z | 2,097,152    | 254          |
| D             | 1110          | 224-239.x.y.z | -            | -            |
| E             | 1111          | 240-254.x.y.z | -            | -            |

8. What is **TCP**
9. What is **UDP**
10. What are the **network layers**
11. What is the **OSI model**
12. What is a **DHCP server** and the **DHCP protocol**
13. What is a **DNS server** and the **DNS protocol**
14. What are the **rules to make 2 devices communicate using IP addresses**
15. How does **routing** work with IP
16. What is a **default gateway** for routing
17. What is a **port** from an IP point of view and what is it used for when connecting to another device
