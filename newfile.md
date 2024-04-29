

# OSI FILE
 -The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network.
 -It was the first standard model for network communications, adopted by all major computer and telecommunication companies in the early 1980s

 -The modern Internet is not based on OSI, but on the simpler TCP/IP model. However, the OSI 7-layer model is still widely used, as it helps visualize and communicate
  how networks operate, and helps isolate and troubleshoot networking problems.

 -OSI was introduced in 1983 by representatives of the major computer and telecom companies, and was adopted by ISO as an international standard in 1984.

   # OSI Model has 7 layers

   #  1 Physical Layer
  
   The physical layer is responsible for the physical cable or wireless connection between network nodes. It defines the connector, the electrical cable or wireless
   technology connecting the devices, and is responsible for transmission of the raw data, which is simply a series of 0s and 1s, while taking care of bit rate control.
  
  #  2 Data Link Layer

   The data link layer establishes and terminates a connection between two physically-connected nodes on a network. 
   It breaks up packets into frames and sends them from source to destination. This layer is composed of two parts—Logical Link Control (LLC),
   which identifies network protocols, performs error checking and synchronizes frames, and Media Access Control (MAC) which uses
    MAC addresses to connect devices and define permissions to transmit and receive data.

  #  3 Network Layer

   The network layer has two main functions. One is breaking up segments into network packets, and reassembling the packets on the receiving end.
   The other is routing packets by discovering the best path across a physical network. The network layer uses network addresses
    (typically Internet Protocol addresses) to route packets to a destination node.

  #  4 Transport Layer

   The transport layer takes data transferred in the session layer and breaks it into “segments” on the transmitting end. 
   It is responsible for reassembling the segments on the receiving end, turning it back into data that can be used by the
   session layer. The transport layer carries out flow control, sending data at a rate that matches the connection speed 
   of the receiving device, and error control, checking if data was received incorrectly and if not, requesting it again.