# Network
## TCP
- The concepts of [TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol) and how it works:
    - What are the meaning of SYN, ACK?
    - How does TCP open a connection? What does it need to open a connection?
    - How does TCP close the connection?
    - Why there are 3 ways handshake but not 2 ways? 
    - Why they have to send 2 "random" sequence numbers? The purpose of this sequence number?
    - What happens if the Internet is dropped in the middle of the connection? Or in case one peer is crashed?
    - What happens if the 3rd handshake failed? How can the server detect it and what does it do in this case?
    - What happens if some bits are wrong due to connection errors? How to detect them and fix them?
    - What happens if some "packet" is missing on the way?
    - How is the timeout handled? What happens if the timeout is expired?
    - How to detect the appropriate number of packets to send (speed of sending packet)?
    - How long can you keep a TCP connection alive?
- What are the differences between TCP and UDP? And in which case we should use TCP/UDP?
