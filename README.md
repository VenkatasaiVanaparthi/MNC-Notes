# MNC-Notes

1 byte = 8 bits
1 Kilobyte = 1024 bytes
1 Megabyte = 1024 Kilobytes
1 Kilobit = 1000 bits
1 Megabit = 1000 Kilobits

### Different Delays

1. Transmission Delay: The time it takes for a packet to be transmitted over a network link from one device to another. This is determined by the size of the packet and the bandwidth of the link.

2. Processing Delay: The time it takes for a device to process a packet before it can be transmitted. This includes the time needed for the device to inspect and potentially modify the packet's header, as well as any other processing that must be done before the packet can be forwarded.

3. Queuing Delay: The time a packet spends waiting in a queue before it can be transmitted. This can happen when multiple packets arrive at a network device at the same time and have to wait their turn to be transmitted.

4. Propagation Delay: The time it takes for a signal to travel across a physical medium, such as a cable or fiber optic line. This is determined by the distance the signal must travel and the speed of the medium.


### Transmission Delay = Packet Size / Bandwidth

where:
Packet Size: The size of the packet being transmitted, usually measured in bits or bytes.
Bandwidth: The rate at which data can be transmitted over the link, usually measured in bits per second (bps).


### Transmission Rate
Suppose that two network endpoints have a round-trip time of 20 milliseconds, and that the sender transmits 8 packets every round trip. What will be the sender’s transmission rate for this round-trip time, assuming 2500-byte packets? Give your answer in bytes per second.

Answer:

Round-trip time(RTT) = 20 milliseconds = 0.02 seconds * 8 packets every round trip

-> 2500-byte packets

Total data per round-trip = 8 packets * 2500-byte packets = 20000 bytes/round-trip Round-trips per second = 1/0.02 = 50

Transmission Rate = Data per round-trip * Round-trips per sec = 20000*50 = 1,000,000 bytes/sec


## Here are some common application layer protocols and their associated transport layer protocols:

### TCP-based protocols:

HTTP (Hypertext Transfer Protocol) for web browsing

FTP (File Transfer Protocol) for file transfer

SMTP (Simple Mail Transfer Protocol) for email transmission

Telnet for remote terminal access

SSH (Secure Shell) for secure remote terminal access

IMAP (Internet Message Access Protocol) for email retrieval

POP3 (Post Office Protocol version 3) for email retrieval

DNS (Domain Name System) for domain name resolution

HTTPS (HTTP Secure) for secure web browsing

### UDP-based protocols:

DNS (Domain Name System) for domain name resolution

DHCP (Dynamic Host Configuration Protocol) for automatic IP address assignment

SNMP (Simple Network Management Protocol) for network management

TFTP (Trivial File Transfer Protocol) for file transfer

RTP (Real-time Transport Protocol) for multimedia streaming

SIP (Session Initiation Protocol) for VoIP (Voice over IP) and video conferencing

NFS (Network File System) for file sharing

NTP (Network Time Protocol) for time synchronization

It's important to note that some protocols, such as SIP and DNS, can use both TCP and UDP depending on the specific application requirements and configuration.
