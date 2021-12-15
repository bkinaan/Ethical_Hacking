# Terms and Definitions
## Abstract
This document will contain all terms and definitions I have researched in my pursuit to explore ethical hacking. Since I am exploring all this with limited knoledge, not everything here will specifically pertain to ethical hacking. I may have just stumbled accross it while looking for anwers across the web. This will not be organized in any way. Other files in this vault will contain more curated information as I begin figuring out how everthing works. The hope is that one day each of these terms will get moved to a supporting document for another topic. Each section below will at least contain the name of the term and the definition of the term. Below the definition there may be additional information (related topics that I think should go together in the future or links to more information -- wikipedia).

*Note: highlighted words/terms are ones that I think should eventually get their own section (basically I don't know what they mean). The goal is to add that section and then link it at the highlight.*

*Note: while internal links (ones that link to other sections of this document) may seem partially unneccessary as they may link to a term defined right above, it allows me to remember what has already been linked in this list when these terms get moved to other more curated files*

## LIST OF UNRELATED WORDS TO ADD
Below is a list of terms I have come across and have yet to define. They currently have no relation (that I know of) with any of the words below so they are here instead.

==Unix-based systems==
==TCP Wrapper==
==ZIP files==
==Multics== [link](https://en.wikipedia.org/wiki/Multics)
==ASCII== [lnk](https://en.wikipedia.org/wiki/ASCII)

---
## Code Signing
**Definition:** Digitally confirming code has not been altered since the original author created it. It employs a cryptographic hash to validate the code.

## Computer Security Exploit
**Definition:** A set of instructions that takes advantage of a bug in the source code to cause unanticipated behavior.

### Types of Exploits
There are many different types of exploits. They are generally classified by how the attacked communicates with the vulnerable software.
*Note: this is NOT an exhaustive list*
#### Remote Exploit
Works over a network, no need to prior access to the vulnerable system 

#### Local Exploit
Requires prior access to the vulnerable system. 

#### Exploits against client applications
Usually consist of a modified server that send an exploit if accessed.

## Social Engineering
**Definition:** A psychologic process that tricks a user into giving confidential information (not always created maliciously). An example of social engineering is the "forgot password" button. It makes it possible for hackers to gain access to the account.

## Black Hat Hacker
**Definition:** A hacker that does it out of personal gain or malice.

## Vunerability
**Definition:** A weakness which can be exploited by a ==threat actor==, such as an attacker, to cross privilege boundaries (i.e. perform unauthorized actions) within a computer system.

List of vulnerabilities can be found [here](https://en.wikipedia.org/wiki/Vulnerability_(computing))

## Attack Vector
**Definition:** A specific path, method, or scenario that can be exploited to break into an IT system, thus compromising secuity.

## Attack Surface:
**Definition:** The sum of the different points (for [[Terms and Definitions#Attack Vector|attack vectors]]) where an unauthorized user (the attacker) can try to enter data to or extract from an enviroment.

*Note:* Keeping the attack surface as small as posible is a basic secuity measure.

## WHOIS
**Definition:** A protocol used for querying databases. It stores the registered users/assignees of an [[Terms and Definitions#Internet Resource|Internet resource]], such as domain name, [[Terms and Definitions#IP Address Blocking|IP address block]], or ==autonomous system==  and stores/delivers the content in a human-readable format.

See [[Terms and Definitions#RWhois|RWhois]], a sister protocol of WHOIS.

## RWhois
**Definition:** A scalable version of WHOIS. It contains a hierarchical tree-like structure. Queries are routed to servers based on specific labels reducing the number of queries that are run throug the primary repository of information.

See [[Terms and Definitions#WHOIS|WHOIS]], the parent protocol of RWhois.

## Internet Resource
**Definition:** Any domain name, electronic address, uniform resource locator (URL), website, mobile app, database, Internet blog, social media site, ==adtech platform==, ==DSP==, ==SSP==, ==data brokers==, or similar online resource

Some examples include: network accesssible documents, ==WAIS databases==, ==FTP servers==, and ==Telnet destinations==.

For more information check out [this](https://en.wikipedia.org/wiki/Internet_resource_locator) article.

## IP Address Blocking
**Definition:** A configuration on a network service that blocks requests hosts from certain IP addresses. Commonly used to protect against ==brute force attacks== and prevent access by a disruptive address. It can also be used to restrict access to/from a specific geographic region. See [[Terms and Definitions#Geo-Blocking|geo-blocking]]

*Note:* services will often log IP address to monitor returning users.

See more [here](https://en.wikipedia.org/wiki/IP_address_blocking).

## Geo-Blocking
**Definition:** A specific case of [[Terms and Definitions#IP Address Blocking|IP address blocking]] that restricts specific geographical locations from accessing a specific [[Terms and Definitions#Internet Resource|internet resouorce]]. Commonly used for restricting certain countries from accessing specific television shows. 

*Note:* A ==VPN== allow people to bypass this restriction.

See more [here](https://en.wikipedia.org/wiki/Geo-blocking).

## Brute Force Attacks
**Definition:** When an attacked repeatedly submitting a password/passphrase in the hope of eventually guessing it correctly. 

An attacked may also choose to attempt an [[Terms and Definitions#Exhaustive Key Search|exhaustive key search]]. 

See more [here](https://en.wikipedia.org/wiki/Brute-force_attack).

## Exhaustive Key Search
**Definition:** An attempt to guess the ==key== tyically created from the password using a ==key derivation function==.

## Key
**Definition:** A peice of information (usually a string of numbers/letters stored in a file) that are processed through a cyprographic algorithm that can encode and decode the data. The strength of the encryption replies on the integrity of the key's security. 

*Note: A key's strength relies on its algorithm, size, generation, and proccess of exchange.*

See more [here](https://en.wikipedia.org/wiki/Key_(cryptography)).

## Internet Geolocation
**Definition:** Software capable of deducing the geographic postion of a device connected to the Internet. 

This information is often gathered using the device's IP address, Wi-Fi hotspots, ==MAC address==, ==image metadata==, or credit card information.

See more [here](https://en.wikipedia.org/wiki/Internet_geolocation).

## Host File
**Definition:** A text file that maps hostnames to their respective IP addresses. It is a plain text file. 

This process was originally manually done and maintainted in a HOSTS.TXT file. Now, the ==Domain Name System (DNS)== automates this process (since the Internet started to get so big). The hostname file still remains a fallback system on many systems.

## Digital Subscriber Line
**Definition:** Technologies used to transmit digital data over telephone lines. Used for Internet access.

The most common DSL technology is ==Asymmetric Digital Subcriber Line== (ADSL).

See more [here](https://en.wikipedia.org/wiki/Digital_subscriber_line).

## Flag Day
A term that represents when an entire system or body of software needs to be restart. This is costly and takes a long time (and really difficult to reverse). It is required when new proccess are not compatible with the old system (problems with backward and forward compatibility). When the two are combined it is called a flag day cutover and alows the system to function after the upgrade. Two major changes are notable flag days. June 14, 1966 (on the U.S.'s actual flag day -- which is where the name comes from) was when ==Multics== redefined ==ASCII== on its operating sysytem. January 1, 1983 was when [[Internet History Support Info#ARPANET|ARPANET]] went from [[Internet History Support Info#Network Control Program|NCP]] to ==TCP/IP==. This change required every node to be shut down and restarted. Imagine the entire Internet needing to be restarted. Today, many systems are designed so that smaller phased-in upgrades are implemented to avoid the need for an entire system restart.

## Internet Protocol Address
Also known as an IP address. A set of numbers that identifies a device connected to the Internet. It is used for recieving data from other devices and keeping record of which device sent data. Currently there are two versions of IP being used. IPv4 uses 4 octents (bytes) seperated by periods to represent a device ID. However, this system only allows for about 4.29 billion devices. Today, with the rapidly growing number of devices connected to the Internet, Cisco expects there to be about 50 billlion devices that will need IP addresses by the end of 2021. So, IPv6 was created to solve this problem. It uses eight sets of a combination of numbers and allows for more than 340 trillion devices. It is also more efficient due to how it is implemented. 

IPv4 example: 104.23.53.88
IPv6 example: 2a00:22c4:a525:c500:423f:cce6:c36b:f64d

## Media Access Control Address
Also known as a MAC address. It represents the ID of a device on a physical network interface. The address is split into two parts. Three sets of hexidecimal numbers represent the comany that made the network interface and the last three sets represent the unique adddres of the network interface. 

MAC address example: a4:c3:f0:85:ac:2d

One concern with MAC addresses is that they can be faked in a proccess known as "spoofing". This allows hackers to gain access to software that was poorly designed and lets any person with a specific MAC address onto the network, such as an admin. In addition, public Wi-Fi will often use MAC address control.

## Internet Control Message Protocol
Also known as ICMP. A supporting protocol to send error messages and operational information during communication. ICMP is different from [[Internet History Support Info#Transmission Control Protocol|TCP]] or [[Internet History Support Info#User Diagram Protocol|UDP]] in that it doesn't acutally send data across a network. Instead, it only notifies the starting host if the destination host or router could not be reached. See more [here](https://en.wikipedia.org/wiki/Internet_Control_Message_Protocol).

## Ping
Uses [[Terms and Definitions#Internet Control Message Protocol|ICMP]] packets to determine the exsistence or reliability of a connection. Ping is the measurement in time it takes for the ICMP to send and receive a packet (using a echo packet and echo reply). Pings can be used to test connections between any IP address. This proccess can be done in terminal using the command `ping <IP Address or website>` 

Example: `ping 128.211.64.61` or `ping www.apple.com`

## Ring Network
A network topology where each node connects to exactly two other nodes. This creates a circle-like ring of nodes. Data travels from node to node through the loop and each node handles all packets. There are two types of ring networks. The first, is a unidirectional ring. This means that all data is travelling in one direction. The problem with this system is that if one link is unable to transfer data, the whole system is unusable. The other type is a bidirectional system meaning that data can travel in either direction around the ring. This is done by creating a counter-rotating ring (C-Ring) that chatches packets from nodes that can't contact the next node (in the case of a broken link). See more [here](https://en.wikipedia.org/wiki/Ring_network).

## Bus Network
A network topology where each node is connected on a network to a "station" node. The station node takes in all incoming traffic and sends it equally accross all the other nodes. Bus networks are good for small networks and are easily able to accomidate new nodes. However, Bus networks have problems with ==packet loss== due to [[Terms and Definitions#Packet Collisions|collisions]] and a large number of nodes reduces the efficiency. If there is a break in the connection, the entire network either shuts down or is broken into two different networks depending on where the break is. See more [here](https://en.wikipedia.org/wiki/Bus_network).

## Packet Loss
Occurs when packets traveling accross a network fail to get to their destination. This can be caused by errors in transmission, network congestion, or [[Terms and Definitions#Packet Collisions|collisions]]. Packet loss is measured in the percentage of packets recieved versus the total number of packets sent. The [[Internet History Support Info#Transmission Control Protocol|TCP]] is one protocol that is able to detect packet loss and retransmit to ensure reliable data transfer. Some programs allow for a certain amount of packet loss. For example, ==VOIP== does not have a problem with losing a few packets becuase it does not decrease the quality of the data.  

## Packet Collisions
Occurs when two different devices try and send a packet on the same network segement at the same time. This causes a "collision" of data. Usually this happens becuase the two devices are unaware of each other and have no way of knowing if the other is transmitting data. Most networks deply some collision avoidence protocol which restricts only one device to send data at any given time. This reduces the efficiency of networks but increaes reliability. See more [here](https://en.wikipedia.org/wiki/Collision_domain).

## Voice Over Internet Protocol
Also known as Voice Over IP, VOIP, or IP telephony. This system sends voice communcations and multimedia over  [[Internet History Support Info#Internet Protocol|IP]] networks rather than telephone networks. 