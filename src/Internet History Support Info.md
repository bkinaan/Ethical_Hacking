# Support Information
This document contains supporting information and links to external resources. Every topic contained here is related to the Internet. Every section of this document will be linked to [[The History of the Internet|this]] document. You aren't really supposed to read through this document, as it makes more sense if you view it by following the main document.

*Note: Highlighted terms in this document are ones that I think will be defined later and will need to be linked.*

## ARPANET
This was the first wide-area packet-switching network developed and one of the first to use ==TCP/IP== protocols. It was founded by ARPA and became the foundation of the Internet as we know it today. It also eventually used the NCP.

## Information Theory
A scientific study of manipulation, recording, and transfer of digital information. This idea started in the 1920s with Harry Nyquist and Ralph Hartley and was completed by Claude Shannon in the 1940s. The basis of information theory focuses on lossless data compression (ZIP files), lossy data compression (MP3 and JPEG), and channel coding (for [[Terms and Definitions#Digital Subscriber Line|DSL]]). Information theory has become curcial for more than just the Internet. See more [here](https://en.wikipedia.org/wiki/Information_theory).

## MOS Transistors
From the technology company MOS Technology a Metal-Oxide-Semiconductor field-effect transistor (also known as MOSFET, MOS-FET, MOS FET, MOS). It is widely known as the building block of modern elecronics (its actually the most shipped electronic device in history -- estimataed 13 trillion units). There are other transistors out there, but they required more input to control the load current (in case you don't know, transistors work as switches for modern computer chips). [Here](https://www.explainthatstuff.com/howtransistorswork.html) is some more information on how transistors work and are built. Basically, MOS transistors work more efficiently, are more scalable, are more easily miniturized, allow for much higher density, are easy to build, and best of all are so much cheaper. See more [here](https://en.wikipedia.org/wiki/MOSFET).

## Time-Sharing
A way to share computer resources to multiple users by using multithreading and multiprogramming. This was a huge change in current computing at the time. Now, companies could have multiple people all use the same computer, reducing the cost of giving each employee their own computing power. This also prompted the creation of interactive applications. See more [here](https://en.wikipedia.org/wiki/Time-sharing).

## Packet Switching
Instead of sending entire files at once, the data is broken up into "packets" which could each follow a different route to their destination. This allowed networking systems to avoid being slowed down by large amounts of data. Packets are made of a header and a payload. The header is used to ensure the network sends the packet to the correct location. The payload contains the information that is part of a larger file. This payload is unpacked by a process at its destination and rebuilt into the complete file (more on this later in the article). See more [here](https://en.wikipedia.org/wiki/Packet_switching).

## Network Control Program
Also known as the NCP, this program ran on the ARPANET. It used user's email addresses to establish connetions. It assinged two ports (each called a simplex port) to each user's application/protocol. Later, ==TCP== and ==UDP== which replaced the NCP only needed to use a single port (called a duplex port).

## TCP
Half of the Internet protocol suite. A set of protocols used in computer networks. 