# First recording (07/06/2021)
## What is a network
- A collection of devices that are connected to each-other
- Main idea is to be able to exchange data
Main Network components are the host/end device

Any device connected to the network that exchanges data is a host/ end device

Devices on the network that are assigned an address for communication purposes

Servers are a software providing a service to other devices on the network

Client is a device that requests for a service

Server client architecture, one requests (client), one provides (server)

Peer to peer, both can ask for services from each other
- Printer and pc is a peer to peer architecture

Intermediary devices connect the end devices to the network (wireless router, router, LAN switch, multilayer switch, Firewall Appliance)

In the network to connect the end devices or to provide a function to the end devices

Network media:
-	Metal wires (cable)
-	Fibre optics
-	Wireless (any)

Main four categories (host, server/client, intermediary devices, network media)

Network types:
-	Size of the area covered
-	Number of users connected
-	Type of services (provided by the network)
-	Area of responsibility ((LAN, your responsibility) (WAN, not your responsibility))
Most common networks 
-	LAN (local area network)
o	Network in a small geographical area (house)
-	WAN (wide area network)
o	Network infrastructure that provides network connection over a large geographical location (internet (collection of WANs))
-	MAN (metro area network (basically a WAN))

Internet: (interconnected network (public)(worldwide)) 
![img_1.png](internet.png)
red line is WAN
    
blue is LAN 

intranet (private connection (company only))

- refers to a private connection of LANs and WANs in a company

extranet (not really used, not well defined (suppliers, customers collaborators))
- secure and safe access between different orgs

communication fundamentals:

formed of three elements
-	Message source (sender)
-	Message destination (receiver)
-	Channel 

Goal = to transmit a message over the channel

Transmit the source message to the destination message over the channel

Message delivery options
-	Unicast (send message to one destination)
-	Multicast (multiple destinations)
-	Broadcast (all destinations)

# Second recording (07/06/2021)
Protocol suite/standards

A group of inter-related protocols, each one performs a specific task

Iso TCIP

Developed by ISO and ITU

OSI is a standard (the concept)

(picture is osi model layer (open systems interconnection))
![img_2.png](OSI.png)

Physical = physical attributes of the connection, uses network media, can find out network speeds here

Data link = layer that takes care of the protocols, describes methods of exchanging data between the protocols, where you define the network and physical addressing

Network = addressing and routing are the main functionalities of this layer, provides services to exchange data across networks Ips are on this layer, to give an address to the host, or any device on the network. Also determines the routing

Transport = Main protocols TCP (Transmission control protocol) reliable and ensures all data arrives at the destination (email)

Session = want to send data, creates a connection between the host and the client. Session is a connection between the sender and the receiver, goes through authentication, have to go through multiple parameters

UDP (User datagram protocol) similar transport layer, does not provide reliability or flow control but it is faster (streaming)

Session, presentation and application have been merged into one layer, Application

Related to the application and the software running
