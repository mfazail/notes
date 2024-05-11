---
navigation.title: "CN ch 5"
---
CN CH5 

1. **Process-to-Process Delivery**:
   The transport layer ensures that data is reliably delivered from one process on a source device to a specific process on a destination device. It adds addressing information to data to ensure proper delivery.

2. **UDP (User Datagram Protocol)**:
   UDP is a connectionless transport protocol that provides a simple and lightweight way to transmit data. It is often used for applications where low overhead and speed are more important than reliability.

3. **TCP (Transmission Control Protocol)**:
   TCP is a connection-oriented transport protocol that ensures reliable, ordered, and error-checked delivery of data. It establishes a connection before data transfer and manages acknowledgments and retransmissions.

4. **Congestion Control Algorithms**:
   Congestion control manages the flow of data within a network to prevent network congestion. Two common algorithms are:
   - **Leaky Bucket Algorithm**: Regulates the data flow rate by allowing data to be transmitted at a constant rate, preventing bursts of traffic that could lead to congestion.
   - **Token Bucket Algorithm**: Controls the rate at which data can be sent into the network by using tokens to represent available transmission opportunities.

5. **Quality of Service (QoS)**:
   QoS refers to techniques and mechanisms used to ensure that certain data traffic receives priority treatment in terms of bandwidth, latency, and reliability. QoS helps maintain a certain level of service for specific applications or data types.
