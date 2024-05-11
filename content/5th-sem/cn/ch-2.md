---
navigation.title: "CN ch 2"
---

CN CH2 

1. **Types of Errors**:
   Errors can occur during data transmission due to noise or other disturbances. There are three main types of errors:
   - **Single-Bit Errors**: When one bit changes value.
   - **Burst Errors**: Multiple bits in a sequence are affected.
   - **Random Errors**: Occur unpredictably.

2. **Framing [Character and Bit Stuffing]**:
   Framing involves delineating the boundaries of data frames in a bit stream. Character stuffing adds a special character before and after the frame, while bit stuffing involves adding extra bits to indicate the start and end of a frame.

3. **Error Detection & Correction Methods**:
   Error detection methods like Parity, Checksum, and Cyclic Redundancy Check (CRC) are used to identify errors in transmitted data. Error correction methods like Hamming codes can correct certain errors.

4. **Flow Control**:
   Flow control manages the rate of data transmission between sender and receiver to prevent congestion and buffer overflow. Techniques like Stop-and-Wait, Sliding Window, and Selective Repeat are used for flow control.

5. **Protocols: Stop & Wait ARQ**:
   Stop-and-Wait Automatic Repeat reQuest (ARQ) is a simple protocol for flow control and error recovery. The sender sends one frame and waits for an acknowledgment from the receiver before sending the next frame. If acknowledgment isn't received, the sender retransmits the frame.
