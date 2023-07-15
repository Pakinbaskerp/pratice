# OSI Model

A conceptual framework known as the OSI (Open Systems Interconnection) model standardizes communication system functions into seven different levels. The OSI model's layers each have a specialized purpose and work together to facilitate communication across various systems and devices. This page gives a summary of the layers in the OSI model.

![layers](https://media.geeksforgeeks.org/wp-content/uploads/20210220204638/cn1.png)


## Table of Contents
- [OSI Model](#osi-model)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [OSI Model Layers](#osi-model-layers)
    - [Layer 1: Physical Layer](#layer-1-physical-layer)
    - [Layer 2: Data Link Layer](#layer-2-data-link-layer)
    - [Layer 3: Network Layer](#layer-3-network-layer)
    - [Layer 4: Transport Layer](#layer-4-transport-layer)
    - [Layer 5: Session Layer](#layer-5-session-layer)
    - [Layer 6: Presentation Layer](#layer-6-presentation-layer)
    - [Layer 7: Application Layer](#layer-7-application-layer)
  - [Conclusion](#conclusion)

## Introduction

The International Organization for Standardization (ISO) created the OSI model to offer a framework for creating and comprehending computer network protocols. It separates the communication process into many levels, each of which is in charge of carrying out particular duties. The layering idea promotes compatibility across various vendors and technologies and aids in the modularization of network operations.

## OSI Model Layers

The OSI model consists of seven layers, each representing a different aspect of the communication process. These layers are:

### Layer 1: Physical Layer


![1st layer](https://media.geeksforgeeks.org/wp-content/uploads/20230405124830/data-bits.jpg)

The physical layer is the bottom layer in the OSI reference model. The actual physical connection between the devices is under its control. Information in the form of bits is present in the physical layer. It is in charge of sending certain bits from one node to the next. As soon as data is received, this layer takes the signal and converts it into 0s and 1s before sending them to the Data Link layer, which rejoins the frame.  



### Layer 2: Data Link Layer
![2nd layer](https://media.geeksforgeeks.org/wp-content/uploads/20230405130015/DatalinkLayer-660x335.jpg)

The message is delivered from node to node through the data connection layer. This layer's primary responsibility is to provide error-free data flow from one node to another via the physical layer. It is the duty of the DLL to transmit a packet to the host using its MAC address when it enters a network. 
There are two sublayers that make up the data link layer:  

Media Access Control (MAC)<br>Logical Link Control (LLC)

### Layer 3: Network Layer

The network layer facilitates the transfer of data between hosts that are part of various networks. It also handles packet routing, which is the choice of the quickest route among a variety of options to transmit the packet. The network layer inserts the IP addresses of the sender and recipient in the header. 


### Layer 4: Transport Layer

The transport layer transfers services from the network layer to the application layer. Segments are the name for the data in the transport layer. It is in charge of ensuring that the entire message is delivered from beginning to end. Additionally, the transport layer offers confirmation of a successful data transmission and retransmits the data if a mistake is discovered.

To guarantee appropriate data transfer on the sender's end, the transport layer gets the prepared data from the top levels, conducts segmentation, and also provides flow and error control. Additionally, it adds Source and Destination port numbers to its header before sending the network layer with the split data. 

Usually, either manually or by default, this destination port number is specified. For instance, a web application normally uses port 80 when requesting a web server because this is the standard port given to web applications. Numerous apps have set default ports. 

The Transport Layer at the recipient's end reads the port number from the header and sends the data it has received to the appropriate application. The segmented data are additionally sequenced and reassembled. 
### Layer 5: Session Layer
![4 layer](https://media.geeksforgeeks.org/wp-content/uploads/20230405124947/communication.jpg)

The Session Layer establishes, manages, and terminates sessions between communicating devices. It enables synchronization, checkpointing, and recovery of data exchange. This layer ensures that data is delivered in the correct sequence and can handle interruptions or restarts in communication.

### Layer 6: Presentation Layer

The Presentation Layer is responsible for data representation and conversion. It deals with data formatting, encryption, compression, and translation. This layer ensures that data from the Application Layer is transformed into a compatible format for transmission.

### Layer 7: Application Layer

The Application Layer provides services directly to end-users or applications. It includes protocols for tasks such as file transfer, email, web browsing, and remote login. HTTP, FTP, SMTP, and DNS are examples of protocols that operate at the Application Layer.

## Conclusion

The OSI model is a fundamental framework for understanding and designing network communication systems. It divides the communication process into seven layers, each with its specific responsibilities. By adhering to the standards defined by the OSI model, network engineers, and developers can ensure interoperability, modularity, and scalability in their network implementations.

For a more detailed understanding of the OSI model and its layers, refer to the official documentation provided by the International Organization for Standardization (ISO).

