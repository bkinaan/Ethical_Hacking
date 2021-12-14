# Support Information
This document contains supporting information and links to external resources. Every topic contained here is related to the Internet. Every section of this document will be linked to [[The History of the Internet|this]] document. You aren't really supposed to read through this document, as it makes more sense if you view it by following the main document.

*Note: Highlighted terms in this document are ones that I think will be defined later and will need to be linked.*

---

## Topics Not Used in the Document
If at the end of the Internet History document terms here were not used, they will be compiled and listed here for reference.

---

## ARPANET
This was the first wide-area packet-switching network developed and one of the first to use [[Internet History Support Info#Transmission Control Protocol|TCP]]/[[Internet History Support Info#Internet Protocol|IP]] protocols. It was founded by ARPA and became the foundation of the Internet as we know it today. It also eventually used the NCP. See more [here](https://en.wikipedia.org/wiki/ARPANET).

## Information Theory
A scientific study of manipulation, recording, and transfer of digital information. This idea started in the 1920s with Harry Nyquist and Ralph Hartley and was completed by Claude Shannon in the 1940s. The basis of information theory focuses on lossless data compression (ZIP files), lossy data compression (MP3 and JPEG), and channel coding (for [[Terms and Definitions#Digital Subscriber Line|DSL]]). Information theory has become curcial for more than just the Internet. See more [here](https://en.wikipedia.org/wiki/Information_theory).

## MOS Transistors
From the technology company MOS Technology a Metal-Oxide-Semiconductor field-effect transistor (also known as MOSFET, MOS-FET, MOS FET, MOS). It is widely known as the building block of modern elecronics (its actually the most shipped electronic device in history -- estimataed 13 trillion units). There are other transistors out there, but they required more input to control the load current (in case you don't know, transistors work as switches for modern computer chips). [Here](https://www.explainthatstuff.com/howtransistorswork.html) is some more information on how transistors work and are built. Basically, MOS transistors work more efficiently, are more scalable, are more easily miniturized, allow for much higher density, are easy to build, and best of all are so much cheaper. See more [here](https://en.wikipedia.org/wiki/MOSFET).

## Time-Sharing
A way to share computer resources to multiple users by using multithreading and multiprogramming. This was a huge change in current computing at the time. Now, companies could have multiple people all use the same computer, reducing the cost of giving each employee their own computing power. This also prompted the creation of interactive applications. See more [here](https://en.wikipedia.org/wiki/Time-sharing).

## Packet Switching
Instead of sending entire files at once, the data is broken up into "packets" which could each follow a different route to their destination. This allowed networking systems to avoid being slowed down by large amounts of data. Packets are made of a header and a payload. The header is used to ensure the network sends the packet to the correct location. The payload contains the information that is part of a larger file. This payload is unpacked by a process at its destination and rebuilt into the complete file (more on this later in the article). See more [here](https://en.wikipedia.org/wiki/Packet_switching).

## Network Control Program
Also known as the NCP, this program ran on the ARPANET. It used user's email addresses to establish connetions. It assinged two ports (each called a simplex port) to each user's application/protocol. Later, [[Internet History Support Info#Transmission Control Protocol|TCP]] and [[Internet History Support Info#User Diagram Protocol|UDP]] which replaced the NCP and only needed to use a single port (called a duplex port). See more [here](https://en.wikipedia.org/wiki/Network_Control_Program).

## Transmission Control Protocol
Commonly called the TCP. Half of the Internet protocol suite. A set of protocols used in computer networks to moderate the transfer of information. This protocol requires a connection (and completes a system test to ensure that connection actually works) to send information. Its complement is the [[Internet History Support Info#Internet Protocol|IP]]. This system provides a secure and reliable system for sending bytes between applications running on hosts that communicate over a network. See more [here](https://en.wikipedia.org/wiki/Transmission_Control_Protocol).

## Internet Protocol
Commonly called the IP. Its main goal is to deliver packets from the source host to the destination host using packet headers. For more information see [[Internet History Support Info#Packet Switching|packet switching]]. It is a complement to the [[Internet History Support Info#Transmission Control Protocol|TCP]]. This system esentially establishes the Internet. The most up-to-date version of IP is IPv6 (Internet Protocol Version 6) and has been in use since 2006. See more [here](https://en.wikipedia.org/wiki/Internet_Protocol).

## User Diagram Protocol
Commonly called the UDP. The difference between [[Internet History Support Info#Transmission Control Protocol|TCP]] and UDP is that UPD does not require a prior connection to send data. This means that there is no reliablity in gettng the information to be recieved at all. If there is the chance for data to be lost along the way, the TCP is recommended instead. UDP is often used in systems where error checking is unnecessary or done in the application. The upside to TCP is thta UDP is much faster as it doesn't need to spend time ensuring all data as been received (and needing to resend whatever is missing). If missing packets are acceptable, UDP is suitable. See more [here](https://en.wikipedia.org/wiki/User_Datagram_Protocol).

## National Physical Laboratory Network
Also known as the NPL Network or NPL Data Communications. A local area computer network. Implemented [[Internet History Support Info#Packet Switching|packet switching]] and high-speed links. It ran off a design proposed by Donald Davies. There were two versions Mark I (1969 - 1973) and Mark II (1973 - 1986). See more [here](https://en.wikipedia.org/wiki/NPL_network).

## CYCLADES
A French research network that used [[Internet History Support Info#Packet Switching|packet switching]] and was solely designed for [[Internet History Support Info#Internetworking|internetworking]]. This system forced host systems be responsible for successful delivery of information instead of having the network system do this. This concept came to be known as the [[Internet History Support Info#End-To-End Principle|end-to-end principle]].

## Internetworking
Connecting multiple computer networks. It allows any two computers to exchange messages without needing to worry about their respective level of networking hardware. The term comes from *inter* and *networking*. Before this term was used, the term catenet (combination of *con*catination and *net*works). Eventually this was all shortented to Internet. See more [here](https://en.wikipedia.org/wiki/Internetworking).

## End-To-End Principle