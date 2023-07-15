# OSI Model

The OSI (Open Systems Interconnection) model is a conceptual framework that standardizes the functions of a communication system into seven distinct layers. Each layer in the OSI model has a specific role and interacts with adjacent layers to enable communication between different devices and systems. This documentation provides an overview of the OSI model and its layers.

![layers](https://media.geeksforgeeks.org/wp-content/uploads/20210220204638/cn1.png){ width="800" height="600" style="display: block; margin: 0 auto" }
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

The OSI model was developed by the International Organization for Standardization (ISO) to provide a framework for designing and understanding computer network protocols. It divides the communication process into a series of layers, each responsible for specific tasks. The layering concept helps in modularizing network functionality and enables interoperability between different vendors and technologies.

## OSI Model Layers

The OSI model consists of seven layers, each representing a different aspect of the communication process. These layers are:

### Layer 1: Physical Layer

The Physical Layer is the lowest layer of the OSI model and deals with the physical transmission of data over a network. It defines the electrical, mechanical, and procedural aspects of the physical medium, such as cables, connectors, and signaling methods.

### Layer 2: Data Link Layer

The Data Link Layer provides reliable and error-free data transfer between adjacent network nodes. It is responsible for framing data into frames, error detection and correction, and managing access to the physical medium. Ethernet, Wi-Fi, and Point-to-Point Protocol (PPP) are examples of protocols that operate at this layer.

### Layer 3: Network Layer

The Network Layer facilitates the delivery of data packets across multiple networks. It handles logical addressing, routing, and packet forwarding. IP (Internet Protocol) is a commonly used protocol at this layer, and routers operate at Layer 3.

### Layer 4: Transport Layer

The Transport Layer ensures reliable and orderly delivery of data between end systems. It provides end-to-end error recovery, flow control, and multiplexing of data streams. Transmission Control Protocol (TCP) and User Datagram Protocol (UDP) are prominent protocols at this layer.

### Layer 5: Session Layer

The Session Layer establishes, manages, and terminates sessions between communicating devices. It enables synchronization, checkpointing, and recovery of data exchange. This layer ensures that data is delivered in the correct sequence and can handle interruptions or restarts in communication.

### Layer 6: Presentation Layer

The Presentation Layer is responsible for data representation and conversion. It deals with data formatting, encryption, compression, and translation. This layer ensures that data from the Application Layer is transformed into a compatible format for transmission.

### Layer 7: Application Layer

The Application Layer provides services directly to end-users or applications. It includes protocols for tasks such as file transfer, email, web browsing, and remote login. HTTP, FTP, SMTP, and DNS are examples of protocols that operate at the Application Layer.

## Conclusion

The OSI model is a fundamental framework for understanding and designing network communication systems. It divides the communication process into seven layers, each with its specific responsibilities. By adhering to the standards defined by the OSI model, network engineers and developers can ensure interoperability, modularity, and scalability in their network implementations.

For a more detailed understanding of the OSI model and its layers, refer to the official documentation provided by the International Organization for Standardization (ISO).

