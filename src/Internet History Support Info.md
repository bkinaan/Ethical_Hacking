# Support Information
This document contains supporting information and links to external resources. Every topic contained here is related to the Internet. Every section of this document will be linked to [[The History of the Internet|this]] document. You aren't really supposed to read through this document, as it makes more sense if you view it by following the main document.

*Note: Highlighted terms in this document are ones that I think will be defined later and will need to be linked.*

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
A French research network that used [[Internet History Support Info#Packet Switching|packet switching]] and was solely designed for [[Internet History Support Info#Internetworking|internetworking]]. This system forced host systems to be responsible for successful delivery of information instead of having the network system do this. This concept came to be known as the [[Internet History Support Info#End-To-End Principle|end-to-end principle]]. This system reduced the chance for errors to occur while data was travelling across a network (becuase there were no intermediary points). Some core features of CYCLADES was integrated in [[Internet History Support Info#ARPANET|ARPANET]]. See more [here](https://en.wikipedia.org/wiki/CYCLADES).

## Internetworking
Connecting multiple computer networks. It allows any two computers to exchange messages without needing to worry about their respective level of networking hardware. The term comes from *inter* and *networking*. Before this term was used, the term catenet (combination of *con*catination and *net*works). Eventually this was all shortented to Internet. See more [here](https://en.wikipedia.org/wiki/Internetworking).

## End-To-End Principle
A design framework for computer networking. The application was located in the end nodes rather than a set of intermediary nodes (gateways and routers). The network is not responsible for ensuring correctness of data, that falls on the application instead. See more [here](https://en.wikipedia.org/wiki/End-to-end_principle).

## X.25
This was a network that was initially developed by the Internation Telegraph anad Telephone Consultive Commitee (ITU-T). It is located in a ==WAN== It used the idea of [[Internet History Support Info#Virtual Circuits|virtual circuits]]. This network was eventually used to create the SERCnet, the predecessor to [[Internet History Support Info#JANET|JANET]]. X.25 was available to common businesses which made it more widely availiable than [[Internet History Support Info#ARPANET|ARPANET]]. It allowed the British Post Office, Western Union International, and Tymnet to collaborate and create the first international [[Internet History Support Info#Packet Switching|packet switching]] network called the International Packet Swtiched Service (IPSS). A few notable services came out of X.25. Telenet offered an electronic mail service. While it was similar to ARPANET's mail service, it was not available to the general public. Using [[Internet History Support Info#Teleprinter|TTY]], CompuServe offered the first email service offered to the general public. It also offered the first real-time chat and [[Internet History Support Info#CB Simulator|CB Simulator]]. Other networks included America Online (AOL) and Prodigy which provided communication and entertainment. [[Internet History Support Info#FidoNet|FidoNet]] provided online access and was popular to hackers and amateur radio operators. X.25 was a popular network for the USSR and eventually was used in the SFMT -- "San Fransisco to Moscow Teleport" (which was later renamed the Sovam Teleport -- "Soviet-American Teleport"). See more    

## Virtual Circuits
Also called a virtual connection. It is a way to transport data using [[Internet History Support Info#Packet Switching|packet switching]] so that it seems as if there is a physical connection between the start and end node. This is an alternative option to [[Internet History Support Info#Datagrams|datagrams]]. Uses a [[Internet History Support Info#Call Setup|call setup]] to establish a connection. This results in a reliable communication service that limits errors (if there are problems, this system uses [[Internet History Support Info#Error Detection and Correction|error detection]] and [[Internet History Support Info#Automatic Repeat Request|automatic repeat request (ARQ)]] to resend the data). See more [here](https://en.wikipedia.org/wiki/Virtual_circuit).

## Datagrams
Basically, a synonym for packets. Datagrams have both a header and a payload. The header gives instructions for the network to ensure the datagram ends at the proper destination. The payload contains the information that will be used for reconstructing the full set of data at the destination. See more [here](https://en.wikipedia.org/wiki/Datagram).

## Call Setup
A process used for establishing a connection across a network. Uses a [[Internet History Support Info#Signal Protocol|signal protocol]]. It represents the amount of time required to establish a call between two terminals (starting and ending point). See more [here](https://en.wikipedia.org/wiki/Call_setup).

## Signal Protocol
A type of communication protocol for establishing or ending a conection between two communication endpoints. It can also be used to determine the status of the connection. See a list of signaling protcols [here](https://en.wikipedia.org/wiki/Signaling_protocol).

## Error Detection and Correction
A process that ensures that the reliability of data transfer on an unreliable network. When sending data, additional "noise" may interfere or corrupt data trasfer. Error detection identifies the errors in transfer while data correction reconstructs the data. See more [here](https://en.wikipedia.org/wiki/Error_detection_and_correction).

## Automatic Repeat Request
Also known as an automatic repeat query (ARQ). It relies on an acknowledgement from the destination that it recieved the data. If an ackowledgement is not recieved in the specified timeout period, the data is resent and this is repeated until an ackowledgement is recieved. This ensures that the complete set of data is recieved. This is part of the [[Internet History Support Info#Open Systems Interconnection Model|OSI model]]. See more [here](https://en.wikipedia.org/wiki/Automatic_repeat_request).

## Open Systems Interconnection Model
Also called the OSI model standardises communication functions of networking computing. It does not matter which underlying internal structure is being used. This means that more systems are able to communicate without needing to be reconfigured to be on a network. This model can be compared to the [[Internet History Support Info#Transmission Control Protocol|TCP]]/[[Internet History Support Info#Internet Protocol|IP]] protocol suite. There are a total of 7 layers included in this model. See more [here](https://en.wikipedia.org/wiki/OSI_model).

## JANET
A UK research and education network. Most educational and researach organizations in the UK are connected to JANET. It stands for **J**oint **A**cademic **Net**work. JANET is operated by Jisc. It was previously known as the JNT Association and before that the United Kindom Education and Research Networking Associant (UKERNA). See more [here](https://en.wikipedia.org/wiki/JANET).

## Teleprinter
Also known as a teletypewriter, teletype, or TTY. An electromechanical device used for sending a receiving typed messages through either point-to-point or point-to-multipoint configurations. While the teleprinter was first invented in 1830s and 1840s (some of the first uses of electrical engineering), it was also used in user interfaces on mainframe and mini computers. Today, more complex computer terminals are used instead of physical printers, however, the term TTY is still often used to communicate the same idea of sending written data over a network. On the other hand, original teleprinters are still used in aviation and for hearing aid communication over telephone calls. See more [here](https://en.wikipedia.org/wiki/Teleprinter).

## CB Simulator
Basaed on the idea of a [[Internet History Support Info#Citizens Band Radio|CB radio]]. It was first marketed similar to CB radio as multi-user communication over a network was widely unknown (there were "channels" and similar commands to those found on a radio). Even without marketing, CB Simulator was a huge hit and eventually more "channels" were added. Interestingly, the first online wedding happened on CB Simulator. See more [here](https://en.wikipedia.org/wiki/CB_Simulator). 

## Citizens Band Radio
Also known as a CB radio. This radio system is used for short person-to-person communication using two way radios on 40 different channels. It is different that Amateur Radio Service ("ham" radio) as it does not require a lisence and is available for personal and business use. See more [here](https://en.wikipedia.org/wiki/Citizens_band_radio).

## FidoNet
A worldwide computer network. Is part of a [[Internet History Support Info#Bulletin Board Systems|BBS]]. This allowed a service known as NetMail which operates similarly to the internet-based email services we use today. FidoNet was supported on almost every BBS and even some non-BBS services. This allowed FidoNet to be easily upgraded and not need to have a [[Terms and Definitions#Flag Day|flag day]]. It uses a [[Internet History Support Info#Modem|modem]] for data compression. FidoNet grew to be the most popular online network with 40,00 systems and millions of users in the 1990s. With the invention of the Internet which allowed any network to be accessed with the same ease, FidoNet was not as in demand. However, it is still in use today. See more [here](https://en.wikipedia.org/wiki/FidoNet). 

## Bulletin Board Systems
Also known as BBS or Computer Bulletin Board Service (CBBS). It is a server that allows users to connect and have access to upload or download data, read news bulletins, and exchange messages. These systems would become models for the World Wide Web, social networks, and other parts of the Internet. See more [here](https://en.wikipedia.org/wiki/Bulletin_board_system).

## Modem
Also known as a modulator-demodulator. Converts digital data to data that can be used by a telephone or radio device (analog data). Early telephone systems used completely wired connections for transffering data, however, eventually radio systems were integrated to allow the phone itself to be wireless and the modem was wired to the main network. Eventually, analog signals couldn't keep up with new demands from the Internet and cable television required changes to the radio systems. Today, these radio systems have greatly improved and are included in every cellular telephone and smartphone. They are essentially invisible and are able to move data and infinitely faster rates that when they were first invented. See more [here](https://en.wikipedia.org/wiki/Modem).

## Computer Network Types
Computer networks each have their own spatial scope. Below is a list of each type from the most limited to the most broad.

[[Internet History Support Info#Nanoscale|Nanoscale]]
[[Internet History Support Info#Near-Field Communication|Near-field (NFC)]]
[[Internet History Support Info#Body Area Network|Body (BAN)]]
Personal (PAN)
Near-me (NAN)
Local (LAN)
*Note:* Within LAN there are three subsets:
- Home (HAN)
- Storage (SAN)
- Wireless (WAN)

Campus (CAN)
Backbone
Metropolitan (MAN)
*Note:* Within MAN there is one subset:
- Municipal wireless (MWN)

Wide (WAN)
Cloud (IAN)
Internet
Interpalnetary Internet

## Nanoscale
Also known as a nanonetwork. A small scale network made of nanomachines (devices that are only a few hundred nanometers or micrometers in size). They are only able to complete simple tasks (computing, data storing, sensing, actuation). Nanonetworks connect these nanomachines to increase their capability. See more [here](https://en.wikipedia.org/wiki/Nanonetwork).

## Near-Field Communication
Also known as NFC. Communication between two devices that are no more than 4 cemtimeters apart. It contains a low-speed connection that is can be used to [[Internet History Support Info#Bootstrapping|bootstrap]] other wireless connections or data transfers of larger files. NFC devices are used for keycards and contactless payements. NFC can also be used for transferring small files or starting wireless processes. See more [here](https://en.wikipedia.org/wiki/Near-field_communication).

## Bootstrapping
The concept that a process is automatically run on a computer. For example, when booting up a computer, the OS software is automatically run and the OS software automatically runs specific drivers or other software that is neccessary for the function of the computer. See more [here](https://en.wikipedia.org/wiki/Bootstrapping#Applications).

## Body Area Network
Also known as BAN, wireless body area network (WBAN), body sensor network (BSN), medical body area network (MBAN). A wireless network made of wearable computing devices. These devices may be inside the body, mounted on the outside of the body or held in a bag that a person carries. It allows for real-time monitoring of medial records. Most times, a number of sensors are integrated in/around the body to create a complete BAN that allows for computer-assisted rehabilitation or early detection of medical conditions. The sensors can contact a larger network (often a [[Internet History Support Info#Personal Area Network|WPAN]]) so that information can be proccessed by a seperate computer network. BANs are usually used for medical purposes. See more [here](https://en.wikipedia.org/wiki/Body_area_network).

## Personal Area Network